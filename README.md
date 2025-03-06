# FRR BGP Configuration for UnifiOS
bgp.conf - FRR BGP Configuration file

## Upload the configuration
#### Go to Settings -> Routing -> BGP
Create an entry, give it a name and upload the configuration file
![picture](./assets/images/1.png)
![picture](./assets/images/2.png)

---

## Useful commands for troubleshooting
`vtysh -c "show ip bgp neighbor 10.2.0.2 advertised-routes"` - Shows the routes being advertised to neighbor 10.2.0.2
