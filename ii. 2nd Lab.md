# Connecting Mikrotik router and PC to the internet

- If you have DHCP server on the ISP side then
    - `IP` > `Client` > `+` > Select the Interface, Select the DNS option, Select the NTP
- If no DHCP server on the ISP end
    - `IP` > `Address` > `+` > `IP/CIDR` > Select `Interface`
    - `IP` > `Route` > `+` > `Dst Add` `0.0.0.0/0` and `Gateway` `Router IP`
- Create a `Bridge` with the other ethenets.
- Assign the address range IP/subnet on the `Bridge`