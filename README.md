# Ansible Cybersecurity Automation

## Overview
This repository contains Ansible playbooks for automating the configuration of server-side cybersecurity analysts and pentesters. These playbooks facilitate the installation of relevant cybersecurity and pentesting tools, as well as the creation of user accounts for analysts and pentesters.

## Playbooks
### 1. Cybersecurity Analyst Server Configuration
- **Description:** Installs cybersecurity tools on the designated server for cybersecurity analysts.
- **Tools:** Wireshark, Snort, OSQuery, YARA, Volatility, Suricata (additional tools can be added).
- **User Creation:** Creates user accounts for cybersecurity analysts, granting them access to necessary resources.

### 2. Pentesters Server Configuration
- **Description:** Installs pentesting tools on the designated server for pentesters.
- **Tools:** Metasploit-framework, Nmap, Burpsuite Community Edition, SQLMap, Hydra, Aircrack-ng, Wireshark (additional tools can be added).
- **User Creation:** Creates user accounts for pentesters, granting them access to necessary resources.

## Usage
1. Ensure Ansible is installed on your control node.
2. Clone this repository to your local machine.
3. Customize the inventory file (`hosts.ini`) with your server details.
4. Update any necessary variables in the playbooks.
5. Run the desired playbook using the `ansible-playbook` command.

## Requirements
- Ansible installed on the control node.
- Target servers accessible via SSH.
- Proper permissions and credentials for user creation and package installation.

## Contributing
Contributions are welcome! Feel free to submit pull requests, suggest improvements, or report issues.

## License
This project is licensed under the [MIT License](LICENSE).
