# azure-config-demo
example service for configuring an IPSec VPN tunnel connecting with the Azure gateway
 
1. Copy the service root folder into ~/nso-instance/packages . 
2. Navigate to azure-setup/src and run the Makefile. An fxs file will be created and the package can be loaded by nso.
3. Log in to the nso cli. run `packages reload`, azure-setup should result true. 
4. Inside config create a service instance and add the devices you want configured.
5. Commit.
