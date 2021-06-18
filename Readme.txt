This is initial provisioning code for ACI fabric build
Fabric Initialize
Step	Process	Notes
1	Fabric Staged and Cabled	Verify all connectivity is in place at designed.
2	Configure CIMC	Configure CIMC
3	Initialize First APIC	
4	Register All Nodes	Register all switches and APICs
5	show controllers and show switch via ssh	
6	Update Firmware	You can create firmware and maintenance groups via automation located here
7	Add FEX	
Fabric Policies and Profiles
Step	Process	Notes
1	DNS	DNS Profiles
2	NTP	NTP Policy and Profile
3	PSU	PSU Policy and Profile
4	SNMP	SNMP Policy and Profile
5	Syslog	Syslog configuration
6	BGP Route Reflector	BGP Route Reflector configuration select minimum two spines
7	POD	One POD Policy
Fabric Access Policies, Profiles and Infra-OOB
Step	Process	Notes
1	Interface Policies	Interface Policies
2	Switch Pair (VPC Domain)	Switch Pair - vPC Domain
3 & 4	Interface and Leaf Profile	
5	Infra-OOB	
