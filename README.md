IT Security Evaluation Framework (ITSEF)

Welcome to the repository for my Master's thesis project focused on the creation of an IT Security Evaluation Framework (ITSEF). This project encompasses a comprehensive approach to enhancing the security posture of CentOS 7.9 systems, employing a methodology that integrates scanning, hardening, and penetration testing to evaluate and improve system security.
Overview

The ITSEF project is designed to address the critical need for robust IT security measures in today's digital landscape. It involves:

    Scanning Virtual Machines (VMs): Initial security assessments were conducted on VMs to identify vulnerabilities and establish a baseline security level.
    Hardening According to CIS Benchmarks: Systems were hardened to comply with Level 1 of the CIS (Center for Internet Security) Benchmarks for CentOS 7.9, version 3.1, enhancing their defense against unauthorized access and potential attacks.
    Penetration Testing: Post-hardening, systems were subjected to penetration testing to evaluate the effectiveness of the security measures implemented. This process involved simulated attack scenarios to identify any remaining vulnerabilities.

Contents

This repository contains a collection of scripts, images, and outputs related to the project, including:

    Ansible Scripts: Secondary script automating the hardening process based on CIS Benchmark v. 2.2 recommendations.
    Bash Scripts: Main script for automating the hardening process based on CIS Benchmark v. 3.1.
    Hack Attack Outputs: Detailed logs and outputs from penetration testing attempts against the hardened systems, providing insights into potential vulnerabilities and the overall security posture.

Contributing

Contributions to the ITSEF project are welcome. Whether you have suggestions for improving the hardening scripts, additional penetration testing strategies, or any other enhancements, please feel free to open an issue or submit a pull request.
