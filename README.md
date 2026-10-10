<img src="assets/header.svg" alt="Vipin John Wilson, Linux and cloud infrastructure engineer, Stockholm, building DeaconGuard" width="100%">

#### What I'm building

**[DeaconGuard](https://github.com/Cloudopsshell/deaconguard)** is a Linux security scanner with a central server and enrollment-token agents. It checks packages against the official Ubuntu, Debian, RHEL and Amazon Linux advisories and covers file integrity, security configuration and malware (ClamAV, plus optional YARA-X rules). [deaconguard.io](https://deaconguard.io)

```mermaid
flowchart LR
    agent["Agent on each host<br/><small>packages, files, malware</small>"]
    feeds["Vendor advisories<br/><small>Ubuntu · Debian · RHEL · AL</small>"]
    server["<b>DeaconGuard server</b><br/><small>matches + scores</small>"]
    dashboard["Dashboard<br/><small>findings per host</small>"]
    agent -- enrollment token --> server
    feeds --> server
    server --> dashboard
```

![Linux](https://img.shields.io/badge/Linux-daily_driver-c9510c?style=flat-square&logo=linux&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-k3s-326ce5?style=flat-square&logo=kubernetes&logoColor=white)
![Go](https://img.shields.io/badge/Go-00758f?style=flat-square&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-2f74c0?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3572a5?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-2b7a0b?style=flat-square&logo=gnubash&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-b56a00?style=flat-square)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-1f6feb?style=flat-square&logo=githubactions&logoColor=white)

[deaconguard.io](https://deaconguard.io) · [LinkedIn](https://www.linkedin.com/in/vipinjohnwilson)
