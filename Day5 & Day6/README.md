This README outlines a foundational Ethernet LAN switching lab conducted within Cisco Packet Tracer. The network consists of two 2960-24TT switches interconnecting four PCs within a single 192.168.1.0/24 subnet. The primary objective is to observe the mechanics of a Layer 2 environment, specifically how switches populate their MAC address tables by inspecting source MAC addresses and how they handle broadcast traffic—such as ARP requests—when destination information is not yet cached.







By transitioning into simulation mode, you can trace the hop-by-hop journey of frames as they are flooded across the switches to all ports until the target device responds. This hands-on exercise requires the use of standard IOS commands like show mac address-table to verify port mappings and clear mac address-table dynamic to reset the learning process. Ultimately, the lab demonstrates the transition from initial network discovery to efficient unicast communication once the switches have mapped the physical topology to their internal logic.
