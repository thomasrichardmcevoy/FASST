# Network Access Control

## Capability and Deficits
In internal networks, it is key to control traffic flows as an overall control on information flows to prevent data theft.  Furthermore, it should be determined which 
devices should be allowed to join the network to prevent hackers using rogue devices to connect to either wifi or physical network access points.  Finally, being able
to zone the network provides the capability to prevent attacks spreading from one zone to another.  Obviously, lacking any of these capabilities increases exposure to
attacks.

## Mapping to Generic Accimap

|Category | Number |
| --- | --- |
|EES     |      |
|PPAA  | 11|
|TOM   ||
|LAGCM ||
|RBA   ||
|GPB   ||

## Recommended Countermeasures

Use of zoning and intrusion detection devices to control traffic flows should be combined with an operating knowledge of where key assets reside on the network and controlling
data flows appropriately e.g. separating management and data communication channels.  Devices should be able to authenticate themselves to the network and the network should
be able to exclude any devices not capable of doing so.


## References
López, G., Cánovas, O., Gómez, A. F., Jiménez, J. D., & Marín, R. (2007). A network access control approach based on the AAA architecture and authorization attributes. Journal of Network and Computer Applications, 30(3), 900-919.
