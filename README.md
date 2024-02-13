# Rickrollworm.py
## A Self-Replicating Network Worm for Prankster Sysadmins

### Introduction
This project, Rickrollworm.py, is a self-replicating network worm developed as a capstone project for Fullstack Academy. The worm is designed to prank users on a local network by automatically spreading to vulnerable systems and playing the infamous Rick Astley song "Never Gonna Give You Up" (commonly known as the "Rickroll").

### Team Members
(ASTLEY's ANGELS)
- Chris Dayao
- Ben Cobb
- Houston Mcelroy
- Thomas Adams

### Project Scope
The worm scans for IPs on a local network, attempts to gain access to accounts using a list of standard usernames and passwords, and then automatically Rickrolls each user at intervals based on password length. It's a playful demonstration of network vulnerability and the importance of strong passwords.

### Getting Started
To get started with Rickrollworm.py, follow these steps:
1. Set up three machines: one running Kali Linux (Target 1), one running Ubuntu (Ground Zero), and another running Ubuntu (Target 2).
2. Create usernames and passwords on the Kali and Ubuntu 2 machines.
3. Change Kali's localhost to the private IP instead of the loopback address.
4. Create home directories for each user on the other two machines and ensure ownership.
5. Add users to the sudoers group.
6. Allow password authentication and disallow key authentication in ssh.config, then restart SSH.
7. Run `sudo xhost +` on Kali.
8. Add the Rickrollworm.py script to Ubuntu 1 and ensure it is executable and configured with appropriate IP ranges.

### Usage
Once the setup is complete, initiate the worm's deployment from Ubuntu 1. Monitor its activity and enjoy the reactions as it spreads and Rickrolls users on the network.

### Contributing
Contributions to Rickrollworm.py are welcome! Feel free to suggest improvements, report bugs, or submit pull requests. Please review our contribution guidelines before making changes.

### License
This project is licensed under the [MIT License](LICENSE).

### Acknowledgements
We would like to thank [Fullstack Academy](https://www.fullstackacademy.com/) for providing the opportunity to work on this project and learn valuable skills in cybersecurity and network programming.



