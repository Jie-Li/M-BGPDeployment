# M-BGPDeployment


*************Update on 26 July 2021  
The information provided by this repository has been out-of-date. 
Please go to the repository of BGP-M for our latest result and data on BGP-M deployment in the Internet.


***************************************************
This repository stores materials related to our work on M-BGP deployment in the Internet.

There are three documents in the repository: M-BGP_Deployment_by_Hurricane_Electric.txt, Peering_ASes_of_Hurricane_Electric.txt, and Peering_ASes_of_Hurricane_Electric_via_IXP.txt. The data contained in these documents are used in our paper "Anatomy of Multipath BGP Deployment in a large ISP Network", accepted by TMA 2020.

M-BGP_Deployment_by_Hurricane_Electric.txt lists the 950 M-BGP deployment cases by Hurricane Electric (AS6939) identified before 20200510. The format is: 
border router|peeringASN,<neighbor address list by show ip bgp summary (separated by comma)>|prefix,<Next-hop list by show ip bgp route detail (separated by comma)>

Peering_ASes_of_Hurricane_Electric.txt lists the peering ASes of Hurricane Electric at each border router.. The format is:
border router|peering ASN,<list of neighbor addresses (separated by comma)>

Peering_ASes_of_Hurricane_Electric_via_IXP.txt lists the peering ASes of Hurricane Electric via IXP at each border router. The format is:
border router|peering ASN,<list of neighbor addresses (separated by comma)>
