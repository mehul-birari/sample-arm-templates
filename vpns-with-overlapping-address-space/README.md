# Deploy 2 VPNs with overlapping address space


[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmehul-birari%2Fsample-arm-templates%2Fmaster%2Fvpns-with-overlapping-address-space%2Fazuredeploy.json)  

This template enables us to deploy 2 VPNs connected between themselves (using IPSec). In one of them, an extra VNET is created with the same address space as the remote VPN and peered it with the VPN VNet.
(VPN1 in VNET1, VPN2 in VNET2 and VNET2-1 peered with same address space as VNET1) 

