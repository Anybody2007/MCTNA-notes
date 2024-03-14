# Connecting Mikrotik router and PC to the internet

- If you have DHCP server on the ISP side then
  <details>
    - `IP` > `Client` > `+` > Select the Interface, Select the DNS option, Select the NTP
  </details>
- If no DHCP server on the ISP end
  <details>
    - `IP` > `Address` > `+` > `IP/CIDR` > Select `Interface`
    - `IP` > `Route` > `+` > `Dst Add` `0.0.0.0/0` and `Gateway` `Router IP`
  </details>
- Create a `Bridge` with the other ethenets.
- Assign the address range IP/subnet on the `Bridge`
