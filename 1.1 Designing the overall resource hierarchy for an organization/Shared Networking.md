VPC are like physical networks, can have subnets globally. Can also set up global distributed firewall, can be defined through network tags.

VPC Peering can be established to p2p VPCs, but also you can configure shared VPC, which can centralize network management in multiple projects.

Shared networking between cloud and on-prem.

### Cloud VPN: Cloud Router makes connection dynamic, lets Google VPC exchange routes using **BGP**.

### Direct Peering: Puts router in the same public data center as Google Point of Presence. 

### Carrier Peering: Gives access from on-prem network through a ISP network.

### Dedicated Interconnect: Allows 1 or more direct private connections to Google, covered by 99.99% SLA, can be backed by VPN too.

### Partner Interconnect: Useful if Datacenter is physical location that can't reach dedicated interconnect colocation facility, useful if you dont need 10GB/s connection, and can be configured to support mission critical service or apps that can tolerate some downtime. Covered by 99.99% SLA too.

### Cross-Cloud interconnect: dedicated connectivity between GCP and another Cloud provider. Supports adoption of integrated multicloud strategy. 10Gb/s or 100Gb/s