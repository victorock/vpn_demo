This repository contains a WIP demo of cloud vpn (should i call it SDWan? or VPNaaS?).  
The provisioning of sites is done in pairs: (responder, initiator).  

domain/[domain] -> A VPN Domain corresponds to multiple initiators and *1* responser.  

keychain/key/[site]/[appliance] -> Keys to register in the cloud provisioner and connect to the appliance.  

keychain/domain/[domain] -> PSK Key for the domain.  


Useful variables:  
  - `cloud_vpn_name:` -> VPN Domain name.  
  - `cloud_vpn_psk:`  -> Domain's PSK.
  - `cloud_vpn_initiator:` -> The remote site to setup.  




