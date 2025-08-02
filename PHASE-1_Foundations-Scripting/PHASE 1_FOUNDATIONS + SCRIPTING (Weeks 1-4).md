# PHASE 1: FOUNDATIONS + SCRIPTING (Weeks 1-4)

## **Week 1: Networking Fundamentals + Version Control**

### **Networking Fundamentals**

- [ ] **IPv4 addressing and structure** (Understand the 32-bit address format and how IP addresses are structured)
    - [Professor Messer IPv4 video](https://www.youtube.com/watch?v=ddM9AcreVqY) | [Cisco IPv4 documentation](https://www.cisco.com/c/en/us/support/docs/ip/routing-information-protocol-rip/13788-3.html)
- [ ] **IPv6 addressing fundamentals** (Learn the 128-bit address format and why IPv6 is necessary)
    - [NetworkChuck IPv6 explained](https://www.youtube.com/watch?v=ThdO9beHhpA) | [IPv6 official documentation](https://tools.ietf.org/html/rfc4291)
- [ ] **Subnetting calculations and VLSM** (Master calculating subnet ranges, host counts, and variable-length subnet masking)
    - [Sunny Classroom subnetting series](https://www.youtube.com/watch?v=BWZ-MHIhqjM) | [SubnettingPractice.com](https://subnettingpractice.com/)
- [ ] **CIDR notation and network planning** (Understand classless addressing and how to plan network architectures)
    - [PowerCert CIDR explained](https://www.youtube.com/watch?v=z07HTSzzp3o) | [ARIN CIDR guide](https://www.arin.net/resources/guide/cidr/)
- [ ] **TCP vs UDP protocol differences** (Know when each protocol is used and their security implications)
    - [Practical Networking TCP/UDP](https://www.youtube.com/watch?v=uwoD5YsGACg) | [Cloudflare TCP vs UDP](https://www.cloudflare.com/learning/ddos/glossary/user-datagram-protocol-udp/)
- [ ] **Common network ports and services** (Memorize critical ports: 22, 80, 443, 53, 25, 110, 143, 993, 995, 3389, 5432, 3306)
    - [Professor Messer port numbers](https://www.youtube.com/watch?v=g2fT-g9PX9o) | [SANS port reference](https://www.sans.org/security-resources/tcpip.pdf)
- [ ] **OSI model layers and security relevance** (Understand each layer and what security controls apply at each level)
    - [Practical Networking OSI model](https://www.youtube.com/watch?v=vv4y_uOneC0) | [Cloudflare OSI model guide](https://www.cloudflare.com/learning/ddos/glossary/open-systems-interconnection-model-osi/)


### **Version Control \& Git**

- [ ] **Git installation and initial configuration** (Set up Git with proper user credentials and SSH keys)
    - [Git official installation guide](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) | [GitHub SSH setup guide](https://docs.github.com/en/authentication/connecting-to-github-with-ssh)
- [ ] **Basic Git commands workflow** (Master add, commit, push, pull, clone, status, log)
    - [Git and GitHub for Beginners](https://www.youtube.com/watch?v=RGOj5yH7evk) | [Atlassian Git tutorials](https://www.atlassian.com/git/tutorials)
- [ ] **Branching and merging strategies** (Understand feature branches, merge vs rebase, and conflict resolution)
    - [Git branching interactive tutorial](https://learngitbranching.js.org/) | [GitHub flow documentation](https://docs.github.com/en/get-started/quickstart/github-flow)
- [ ] **GitHub repository best practices** (Learn README structure, .gitignore files, and security considerations)
    - [GitHub best practices guide](https://docs.github.com/en/repositories/creating-and-managing-repositories/best-practices-for-repositories) | [GitHub security features](https://docs.github.com/en/code-security)


### **Network Analysis Tools**

- [ ] **Wireshark installation and interface** (Set up Wireshark and understand the capture interface)
    - [Wireshark University setup](https://www.youtube.com/watch?v=TkCSr30UojM) | [Official Wireshark documentation](https://www.wireshark.org/docs/)
- [ ] **Capturing and filtering network traffic** (Learn capture filters vs display filters and common filter syntax)
    - [Wireshark filtering tutorial](https://www.youtube.com/watch?v=3Zb4YHs9T2k) | [Wireshark filter reference](https://www.wireshark.org/docs/dfref/)
- [ ] **Analyzing HTTP/HTTPS traffic** (Identify security issues in web traffic and understand TLS handshakes)
    - [Wireshark HTTP analysis](https://www.youtube.com/watch?v=r0l_54thSYU) | [Wireshark TLS analysis guide](https://wiki.wireshark.org/TLS)
- [ ] **Network troubleshooting with packet analysis** (Use Wireshark to diagnose connectivity and performance issues)
    - [Network troubleshooting with Wireshark](https://www.youtube.com/watch?v=GL2kBB8SnLA) | [Packet analysis methodology](https://www.sans.org/white-papers/1672/)


## **Week 2: Linux Mastery + Python Fundamentals**

### **Linux Command Line Mastery**

- [ ] **File system navigation and structure** (Master ls, cd, pwd, find, locate and understand Linux directory hierarchy)
    - [Linux file system explained](https://www.youtube.com/watch?v=HIXzJ3Rz9po) | [Linux Foundation filesystem guide](https://www.pathname.com/fhs/pub/fhs-2.3.html)
- [ ] **File manipulation and permissions** (Learn cp, mv, rm, chmod, chown, chgrp and permission octal notation)
    - [Linux permissions tutorial](https://www.youtube.com/watch?v=ngJG6Ix5FR4) | [DigitalOcean permissions guide](https://www.digitalocean.com/community/tutorials/linux-permissions-basics-and-how-to-use-umask-on-a-vps)
- [ ] **Text processing with grep, awk, sed** (Master pattern matching, text manipulation, and stream editing)
    - [Grep, awk, sed tutorial](https://www.youtube.com/watch?v=Tc_jntovCM0) | [GNU awk manual](https://www.gnu.org/software/gawk/manual/gawk.html)
- [ ] **Process management and monitoring** (Understand ps, top, htop, kill, jobs, nohup, systemctl)
    - [Linux process management](https://www.youtube.com/watch?v=TJzltwv7jJs) | [Red Hat process management guide](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/managing_monitoring_and_updating_the_kernel/managing-processes_managing-monitoring-and-updating-the-kernel)
- [ ] **Package management systems** (Learn apt/yum/dnf package installation, updates, and repository management)
    - [Linux package management](https://www.youtube.com/watch?v=k_0pzdJWiMk) | [Package management comparison guide](https://www.digitalocean.com/community/tutorials/package-management-basics-apt-yum-dnf-pkg)


### **User and Group Management**

- [ ] **User account creation and management** (Master useradd, usermod, userdel and understand /etc/passwd, /etc/shadow)
    - [Linux user management](https://www.youtube.com/watch?v=jwnvKOjmtEA) | [Red Hat user management guide](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/configuring_basic_system_settings/managing-users-and-groups_configuring-basic-system-settings)
- [ ] **Group management and membership** (Learn groupadd, groupmod, groupdel, gpasswd and group permissions)
    - [Linux group management tutorial](https://www.youtube.com/watch?v=zRw0SKaXSfI) | [Linux groups and permissions guide](https://www.cyberciti.biz/faq/understanding-etcgroup-file/)
- [ ] **Sudo configuration and security** (Configure sudoers file, understand sudo policies and security best practices)
    - [Sudo configuration guide](https://www.youtube.com/watch?v=Hd6_L2fPUB4) | [Sudo security best practices](https://www.digitalocean.com/community/tutorials/how-to-edit-the-sudoers-file)


### **SSH and Remote Access**

- [ ] **SSH key generation and management** (Create RSA/ED25519 keys, understand key exchange, and manage authorized_keys)
    - [SSH keys explained](https://www.youtube.com/watch?v=dPAw4opzN9g) | [GitHub SSH key guide](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
- [ ] **SSH client and server configuration** (Configure /etc/ssh/sshd_config for security, disable password auth, change ports)
    - [SSH hardening guide](https://www.youtube.com/watch?v=Atbl7d_yPug) | [SSH security best practices](https://infosec.mozilla.org/guidelines/openssh)
- [ ] **SSH tunneling and port forwarding** (Learn local, remote, and dynamic port forwarding techniques)
    - [SSH tunneling explained](https://www.youtube.com/watch?v=N8f5zv9UUMI) | [SSH tunneling guide](https://www.ssh.com/academy/ssh/tunneling)


### **Python Programming Fundamentals**

- [ ] **Python installation and environment setup** (Install Python, pip, virtual environments, and understand Python path)
    - [Python installation guide](https://realpython.com/installing-python/) | [Virtual environments tutorial](https://www.youtube.com/watch?v=APOPm01BVrk)
- [ ] **Variables, data types, and operators** (Master strings, integers, floats, booleans, lists, dictionaries, sets)
    - [Python data types tutorial](https://www.youtube.com/watch?v=gCCVsvgR2KU) | [Python official tutorial](https://docs.python.org/3/tutorial/introduction.html)
- [ ] **Control structures and loops** (Understand if/elif/else, for loops, while loops, and loop control statements)
    - [Python control flow](https://www.youtube.com/watch?v=f79MRyMsjrQ) | [Control flow documentation](https://docs.python.org/3/tutorial/controlflow.html)
- [ ] **Functions and modules** (Create functions, understand scope, import modules, and create custom modules)
    - [Python functions tutorial](https://www.youtube.com/watch?v=9Os0o3wzS_I) | [Python modules guide](https://docs.python.org/3/tutorial/modules.html)
- [ ] **File I/O and exception handling** (Read/write files, handle CSV/JSON, and implement try/except blocks)
    - [Python file handling](https://www.youtube.com/watch?v=Uh2ebFW8OYM) | [Exception handling guide](https://docs.python.org/3/tutorial/errors.html)
- [ ] **Working with JSON and APIs** (Parse JSON data, make HTTP requests with requests library)
    - [Python JSON tutorial](https://www.youtube.com/watch?v=9N6a-VLBa2I) | [Requests library documentation](https://docs.python-requests.org/en/latest/)


## **Week 3: Security Concepts + Bash Scripting**

### **Core Security Principles**

- [ ] **CIA Triad deep dive** (Understand confidentiality, integrity, availability and real-world examples)
    - [CIA Triad explained](https://www.youtube.com/watch?v=AJTJN4wDBM8) | [NIST cybersecurity framework](https://www.nist.gov/cyberframework)
- [ ] **Authentication vs Authorization** (Distinguish between identity verification and access control mechanisms)
    - [Authentication vs Authorization](https://www.youtube.com/watch?v=I0poT4UxFxE) | [Auth0 authentication guide](https://auth0.com/intro-to-iam/what-is-authentication/)
- [ ] **Common attack vectors and threats** (Learn about DoS/DDoS, MITM, phishing, malware, and social engineering)
    - [Common cyber attacks](https://www.youtube.com/watch?v=Dk-ZqQ-bfy4) | [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [ ] **Risk assessment and management** (Understand risk = threat × vulnerability × impact and risk mitigation strategies)
    - [Risk management fundamentals](https://www.youtube.com/watch?v=RLk2k1RzEkE) | [NIST risk management framework](https://csrc.nist.gov/Projects/risk-management/about-rmf)


### **Cryptography Fundamentals**

- [ ] **Symmetric vs asymmetric encryption** (Understand AES, RSA, key exchange, and when to use each type)
    - [Cryptography basics](https://www.youtube.com/watch?v=jhXCTbFnK8o) | [Applied Cryptography concepts](https://www.schneier.com/academic/archives/1994/01/introduction_to_cry.html)
- [ ] **Hashing and digital signatures** (Learn SHA-256, MD5 vulnerabilities, HMAC, and signature verification)
    - [Hashing explained](https://www.youtube.com/watch?v=b4b8ktEV4Bg) | [Digital signatures guide](https://www.ssl.com/faqs/digital-signatures/)
- [ ] **PKI infrastructure concepts** (Understand CAs, certificate chains, CRLs, and certificate validation)
    - [PKI explained](https://www.youtube.com/watch?v=heacxYUnFHA) | [PKI components overview](https://www.keyfactor.com/resources/what-is-pki/)
- [ ] **TLS/SSL handshake process** (Learn the step-by-step TLS negotiation and certificate exchange)
    - [TLS handshake explained](https://www.youtube.com/watch?v=86cQJ0MMses) | [Cloudflare TLS guide](https://www.cloudflare.com/learning/ssl/what-happens-in-a-tls-handshake/)


### **Bash Scripting Mastery**

- [ ] **Bash syntax and variables** (Master variable declaration, environment variables, and parameter expansion)
    - [Bash scripting tutorial](https://www.youtube.com/watch?v=tK9Oc6AEnR4) | [Advanced Bash scripting guide](https://tldp.org/LDP/abs/html/)
- [ ] **Conditional statements and logic** (Learn if/elif/else, test conditions, and comparison operators)
    - [Bash conditionals](https://www.youtube.com/watch?v=p0KKBmfiVl0) | [Bash conditional expressions](https://www.gnu.org/software/bash/manual/html_node/Bash-Conditional-Expressions.html)
- [ ] **Loops and iteration** (Master for loops, while loops, and loop control with break/continue)
    - [Bash loops tutorial](https://www.youtube.com/watch?v=8eEgNfP8ELI) | [Bash loop examples](https://linuxhint.com/bash_loop_list_strings/)
- [ ] **Functions and script organization** (Create reusable functions, understand scope, and organize code)
    - [Bash functions guide](https://www.youtube.com/watch?v=qgm2e3r5B-k) | [Shell function best practices](https://google.github.io/styleguide/shellguide.html)
- [ ] **Error handling and debugging** (Implement error checking, use set -e, and debug techniques)
    - [Bash error handling](https://www.youtube.com/watch?v=8Ul-Efi1Xys) | [Bash debugging techniques](https://tldp.org/LDP/Bash-Beginners-Guide/html/sect_02_03.html)
- [ ] **File processing and text manipulation** (Use grep, sed, awk within scripts for log processing)
    - [Bash text processing](https://www.youtube.com/watch?v=1_h3Z9uSJOU) | [Advanced text processing examples](https://www.linuxjournal.com/content/pattern-matching-bash)


### **System Automation Tasks**

- [ ] **Log file parsing and analysis** (Create scripts to parse system logs, web logs, and security logs)
    - [Log analysis with bash](https://www.youtube.com/watch?v=wxa3S_rLoDk) | [System log analysis techniques](https://www.digitalocean.com/community/tutorials/how-to-view-and-configure-linux-logs-on-ubuntu-and-centos)
- [ ] **System monitoring scripts** (Monitor CPU, memory, disk usage, and create alerts)
    - [System monitoring scripts](https://www.youtube.com/watch?v=6p50wnhPLo8) | [Linux system monitoring guide](https://www.tecmint.com/linux-server-monitoring-tools/)
- [ ] **Backup automation scripts** (Create automated backup solutions with scheduling and rotation)
    - [Backup scripts tutorial](https://www.youtube.com/watch?v=Wvb8gZGF9WM) | [Backup best practices](https://www.backblaze.com/blog/the-3-2-1-backup-strategy/)


## **Week 4: PROJECT 1 - Automated VM Hardening**

### **Security Hardening Concepts**

- [ ] **CIS Controls framework understanding** (Learn the 18 CIS Controls and their implementation priorities)
    - [CIS Controls overview](https://www.youtube.com/watch?v=3nSIDDiXFM0) | [CIS Controls v8 documentation](https://www.cisecurity.org/controls/cis-controls-list/)
- [ ] **System baseline and configuration management** (Understand security baselines and configuration drift)
    - [Security baselines explained](https://www.youtube.com/watch?v=YRzWjpI2YVw) | [NIST security baselines](https://csrc.nist.gov/Projects/United-States-Government-Configuration-Baseline)
- [ ] **Service hardening principles** (Learn to disable unnecessary services and secure required ones)
    - [Linux service hardening](https://www.youtube.com/watch?v=Sa5jXD7KzRE) | [Red Hat security hardening guide](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/security_hardening/)


### **Firewall Configuration**

- [ ] **iptables rules and chains** (Master INPUT, OUTPUT, FORWARD chains and rule syntax)
    - [iptables tutorial](https://www.youtube.com/watch?v=qPEA6J9pjG8) | [iptables man page](https://linux.die.net/man/8/iptables)
- [ ] **UFW (Uncomplicated Firewall) setup** (Learn simplified firewall management and application profiles)
    - [UFW firewall tutorial](https://www.youtube.com/watch?v=6w13nPQJO-k) | [UFW documentation](https://help.ubuntu.com/community/UFW)
- [ ] **firewalld configuration** (Understand zones, services, and permanent vs runtime rules)
    - [firewalld guide](https://www.youtube.com/watch?v=q6d7eciC4-8) | [Red Hat firewalld guide](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/configuring_and_managing_networking/using-and-configuring-firewalld_configuring-and-managing-networking)


### **Intrusion Detection and Prevention**

- [ ] **fail2ban installation and configuration** (Set up automated IP banning for failed login attempts)
    - [fail2ban setup guide](https://www.youtube.com/watch?v=fkpB3bD0QFM) | [fail2ban configuration manual](https://github.com/fail2ban/fail2ban/wiki/Configuration)
- [ ] **Log monitoring and alerting setup** (Configure rsyslog, logrotate, and monitoring scripts)
    - [Linux log monitoring](https://www.youtube.com/watch?v=L3LOhJJEGsY) | [rsyslog configuration guide](https://www.rsyslog.com/doc/v8-stable/configuration/index.html)
- [ ] **AIDE (file integrity monitoring)** (Set up file system integrity checking and monitoring)
    - [AIDE setup tutorial](https://www.youtube.com/watch?v=F1oV6QgnLjw) | [AIDE configuration guide](https://aide.github.io/doc/manual.html)


### **Python Security Automation**

- [ ] **Security scanning script development** (Create scripts to check for misconfigurations and vulnerabilities)
    - [Python security scripting](https://www.youtube.com/watch?v=Pms2lWW6hpI) | [Security automation with Python](https://realpython.com/python-security-best-practices/)
- [ ] **Compliance reporting automation** (Generate reports mapping controls to implementations)
    - [Python reporting libraries](https://www.youtube.com/watch?v=1XqTJJp4NYM) | [ReportLab documentation](https://docs.reportlab.com/)
- [ ] **Integration with system APIs** (Use psutil, subprocess, and system calls for automation)
    - [Python system administration](https://www.youtube.com/watch?v=2mcO8Qqb7tQ) | [psutil documentation](https://psutil.readthedocs.io/)


### **Documentation and Testing**

- [ ] **Security documentation best practices** (Create clear, maintainable security documentation)
    - [Technical writing for security](https://www.youtube.com/watch?v=8eewQ1qkdU4) | [Security documentation guide](https://www.sans.org/white-papers/1346/)
- [ ] **Testing and validation procedures** (Develop test cases and validation methods for hardening)
    - [Security testing methodology](https://www.youtube.com/watch?v=8kZe6BSPBGw) | [OWASP testing guide](https://owasp.org/www-project-web-security-testing-guide/)
- [ ] **Version control for security configs** (Manage security configurations with Git)
    - [Git for system administrators](https://www.youtube.com/watch?v=8KCQe9Pm1kg) | [Infrastructure as Code with Git](https://www.atlassian.com/git/tutorials/infrastructure-as-code)


