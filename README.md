
As a personal foray into the development of NSO services I decided to implement the following config using an xml service template:
- Setting up an access control list for cross-premise traffic.
- Set up IPSec and IKE protocols between a local device and a gateway.
- Set up a virtual tunnel interface and bind the IPSec policy to it.
This should allow a local VPN device to connect securely to a Microsoft Azure gateway with added encryption. 
 I found this template to be a good example of how dynamic service templates can help automate many tasks on the NSO platform.
 This is just a sample of how I would go about creating a small service in NSO. I am actively looking for opportunities to break into the network automation space.
 
 If anyone working with NSO is seeking an ambitious junior developer please get in touch at alexorlow17@gmail.com
