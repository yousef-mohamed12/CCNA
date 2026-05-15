Objective: Configure IP addresses and hostnames on PC1, PC2, R1, and R2 according to the network diagram — including default gateways on both PCs — across four networks: 192.168.1.0/24, 192.168.12.0/24, 192.168.13.0/24, and 192.168.3.0/24.









Task: Configure static routes on R1 and R2 so that traffic can be routed between PC1 (192.168.1.0/24) and PC2 (192.168.3.0/24) through the intermediary network (192.168.12.0/24), with R2 also connected via 192.168.13.0/24.
















Verification: Success is confirmed when PC1 can successfully ping PC2, proving end-to-end connectivity across all router hops — switches require no configuration.
