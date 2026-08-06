*This project has been created as part of the 42 curriculum by jhoban.*

# NetPractice

## Description
NetPractice is a training project focused on core networking fundamentals through 10 practical browser-based exercises. The objective is to configure each level so communication works correctly by applying concepts such as TCP/IP addressing, subnet masks, default gateways, routers, switches, and basic OSI layer reasoning.

Each level requires diagnosing connectivity issues and selecting valid addressing and routing values. The project is designed to build understanding of how hosts and network devices interact, not only to produce correct final values.

## Instructions
1. Download the NetPractice training package from the 42 intra project page and extract it locally.
2. Launch the training interface from the extracted folder:
	- Preferred: `./run.sh`
	- Alternative: `python3 -m http.server 49242`, then open `http://localhost:49242`
3. Enter your login in the interface before solving levels.
4. Complete levels `1` to `10`.
5. After each solved level, click **Get my config** to export the configuration file.
6. Submission requirement: place exactly 10 exported configuration files at the repository root, one per level (`level1.json` ... `level10.json`).
7. Before final submission, verify all filenames are correct and each file corresponds to the right level.

## Resources
- 42 project subject and evaluator guidelines for NetPractice.
- RFC 791 (IPv4) and RFC 950 (subnetting fundamentals).
- Cisco Networking Academy introductory materials (IP addressing, subnetting, routing basics).
- Cloudflare Learning Center articles on IPs, routing, and gateways.
- OSI model references for understanding layer responsibilities during troubleshooting.
- Networking concepts studied in this project: TCP/IP addressing, subnet masks, default gateways, routers, switches, and OSI layers.

AI usage note:
AI was used as a study assistant to review explanations and improve documentation clarity. All configurations and networking decisions were validated manually through the NetPractice interface and logs, and the final content is fully reviewed and understood.
