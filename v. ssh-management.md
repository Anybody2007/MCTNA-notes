# SSH Key add

generate your ssh key, windows, linux and mac all can genarate the keys with the below command

```bash
    ssh-keygen -t ed25519 -C "Your-Name"
    cat .ssh/id_ed25519.pub
```

Go to `System` > `User` > `SSH Keys` > `Import` the file


# Disble SSH password login

Go to `System` > `Terminal`

```bash
    ip ssh set always-allow-password-login=no
    ip ssh print
```
**Note this can not be done in GUI mode**