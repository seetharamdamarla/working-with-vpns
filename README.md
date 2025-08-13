# VPN Setup and Traffic Encryption Verification

----

## Objective:
The goal of this task is to understand the role of VPNs in protecting privacy and ensuring secure communication. The task involved setting up a VPN, verifying its functionality, analyzing traffic encryption, and comparing network performance with and without VPN.

----

## Steps Performed:

## 1. VPN Setup:

- Installed ProtonVPN (Free Tier) on my system.
- Connected to a VPN server located in the USA.


## 2. IP Address Verification:
   
- Checked my IP address before VPN connection using whatismyipaddress.com and took a screenshot.
- Verified the IP address after VPN connection and confirmed that it changed to the VPN server’s IP. Screenshot was taken.

## 3. Traffic Encryption Confirmation:
   
- Browsed popular websites like cnn.com and nytimes.com to ensure encrypted traffic.
- Verified that the traffic was using HTTPS protocol by observing the browser URL and traffic in Wireshark.
- Detected QUIC protocol packets in Wireshark, confirming encrypted and secure connections.
- Relevant screenshots were captured.

## 4. Browsing Speed Comparison:
   
- Conducted a speed test using fast.com while connected to VPN.
  Speed: 220 kbps

- Disconnected the VPN and conducted the speed test again.
  Speed: 300 kbps

- Confirmed that VPN slightly reduced the browsing speed due to encryption overhead.

## 5. Research on VPN Encryption and Privacy Features:

- Detailed research was conducted and summarized in a separate document covering:
- VPN encryption standards (AES-256, RSA)
- Privacy features (IP masking, no-logs policy, kill switch, DNS leak protection)
- VPN protocols (OpenVPN, WireGuard, IKEv2)

## 6. Files in the Repository:

| File Name                               | Description                              |
|-----------------------------------------|------------------------------------------|
| before_vpn_ip.png                       | IP address before VPN connection         |
| after_vpn_ip.png                        | IP address after VPN connection          |
| vpn_connected.png                       | ProtonVPN connection status              |
| cnn_com_vpn_access.png                  | Browsing CNN with VPN                    |
| nytimes_vpn_access.png                  | Browsing NYTimes with VPN                |
| proton_vpn_traffic.png                  | Wireshark capture showing VPN traffic    |
| vpn_connection_traffic.png              | Wireshark QUIC/HTTPS traffic evidence    |
| speed_test_with_vpn.png                 | Speed test result with VPN               |
| speed_test_without_vpn.png              | Speed test result without VPN            |
| VPN_Encryption_and_Privacy_Features.txt | VPN encryption and privacy research      |
| VPN_Benefits_and_Limitations.txt        | VPN benefits and limitations summary     |

## VPN Benefits and Limitations:
Detailed documentation on VPN benefits (privacy, encryption, bypassing restrictions) and limitations (reduced speed, blocked sites, trust dependency) provided in the repository.

## Key Learnings:
- Hands-on VPN setup and connection.
- Traffic encryption analysis using Wireshark.
- Practical understanding of VPN impact on speed and privacy.
- Importance of VPN protocols and privacy features.
  
## Conclusion:
I successfully set up and used ProtonVPN to protect my online privacy. I verified that the VPN effectively changed my IP address and encrypted my browsing traffic. The browsing speed slightly decreased while connected to the VPN, which is expected due to encryption overhead. <br>
Overall, I gained practical experience in using VPNs for secure and private internet usage.

