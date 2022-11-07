<h2></h2>
<br />
Network Firewall Configuration in Compliance with Security Policy Documentation: Cisco ASA Firewall. Identifying any findings of non-compliance.
The firewall configuration is compared to approved ports, protocols and services in accordance with policy from the ITSecurity Department.The firewall has port 165 open and it has not been authorized by IT Security.
1.X.X Documentation of business justification and approval for use of all services, protocols, and ports allowed, including documentation of security features implemented for those protocols considered to be insecure.
<br />
<img src="https://imgur.com/fc8NQRm.png" height="58%" width="58%" alt="Disk Sanitization Steps"/>

<br />
Sonicwall Firewall Rules : You don't want unknown traffic in a network that is unauthorized. Any source, any destination should be denied.
1.X.X Restrict inbound and outbound traffic to that which is necessary for the cardholder data environment, and specifically deny all other traffic.
<br />
<img src="https://imgur.com/t4NmNjW.png" height="58%" width="58%" alt="Disk Sanitization Steps"/>

<br />
RTA is in scope, yet system hardening needs to be in place so PCI network isn't breached through weak RTA. Configurations should provide IP addresses since they are missing from the diagram.
<br/>
<img src="https://imgur.com/OORfQ7j.png" height="58%" width="58%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://imgur.com/gMrJoIX.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>

<br />
PCI DSS Requirement 1.X.X: Install perimeter firewalls between all wireless networks and the cardholder data environment, and configure these firewalls to deny or, if traffic is necessary for business purposes, permit only authorized traffic between the wireless environment and the cardholder data environment.
Network Diagram:
<br />
<img src="https://imgur.com/uckLYrt.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>


