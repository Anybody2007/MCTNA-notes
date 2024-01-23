**Long Term -** Releases that are stable for a long time

**Stable -** Releases that are bug free

**Beta -** Self explainatory. Lots of bugs.

**Archive -** Long term update after serving long time. Funny~!~

# How to updgrade using Internet

- `System` > `Packages` > `Check for updates`
- `Download` - Downloaded in the files then after manual reboot the update will happen
- `Download&Install` - Agrasive download and install now

## How to download the update from web

`mikrotik.com` > `Downloads` > `Archive`

## How to identify the architecture of the Router

- `System` > `Resources` > `Architecture Name`

# How to upgrade without internet, only with other Router

- Keep the update package in your desired router. But both router should be accessible by each other.
- Now go to the target router
    - `System` > `Auto Upgrade` > Add `Update Package Sources` with `IP`, `username`, `password`.
    - `Refresh` > `Download`
    - now reboot

# How to downgrade the Router

- Keep the dwongraded downloaded package in the files section in Mikrotik.
- `System` > `Packages` > `Downgrade`

# Routerboard Firmware Update

- `System` > `Routerboard`
- Good choice to keep these updated.