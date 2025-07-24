# Born2beroot

> [!IMPORTANT]
> None of my code is publicly available here, but if you're a recruiter, I'd be happy to share it with you upon request.

<p align="center">
<img width="317" height="268" alt="Screenshot from 2025-07-23 08-57-06" src="https://github.com/user-attachments/assets/bfae2c73-7a26-403d-acda-06b6cd9f967a" />
</p>

The ***Born2beroot*** project is a foundational system administration assignment at 42 that introduces the basics of managing a secure Linux system. The goal is to install and configure a virtual machine running a Debian-based OS (typically Debian or Rocky Linux) and apply a set of strict security and configuration rules, simulating the role of a junior sysadmin.
This project focuses on understanding Linux system structure, user management, permissions, firewalls, and services — all through hands-on configuration and command-line work.

What I had to do:
* Install a virtual machine using VirtualBox or UFW-compatible Linux
* Set up a LVM partitioning scheme during installation
* Configure sudo with limited permissions using the `sudo` group
* Create a non-root user with strong password policy enforcement
* Set up **UFW** (Uncomplicated Firewall) with specific rules
* Install and configure **SSH** with secure settings (e.g., disable root login)
* Set up a system monitoring script (e.g., `monitoring.sh`) that:
* Reports CPU usage, memory, disk, **LVM** status, and user activity
* Sends system info via broadcast or logs
* Configure **cron** jobs to schedule regular script execution
* Ensure proper host and hostname naming conventions

Bonus Part: Hardening & Services
* For the bonus, I extended the project by:
  * Enforcing stricter password rules (via PAM) and expiration policies
  * Limiting SSH access to specific users and IP ranges
  * Installing and configuring additional tools (e.g., fail2ban for brute-force protection)
  * Exploring the use of apt audit or Lynis for further system hardening

What I Learned:
* How to install and configure a Linux system from scratch
* Disk partitioning with **LVM** and understanding mounting/volume logic
* Core Unix concepts: users, groups, permissions, services
* Managing services with systemd and securing access via **UFW** and **SSH**
* Writing and scheduling shell scripts for system monitoring and automation
* The importance of security policies and compliance (strong passwords, user roles, auditability)

Born2beroot was a deep dive into the essentials of system administration. It taught me to approach Linux not just as a user, but as someone responsible for the reliability, security, and maintainability of the machine. It laid the groundwork for understanding how production servers are managed and secured in the real world.
