# Security Research Project

This repository documents a comparative security assessment conducted against versions 3.4.3 and 3.4.5 of a containerised software system. The assessment aimed to identify and evaluate network exposure, software vulnerabilities, and risks related to outdated dependencies and insecure configurations within both the host environment and Docker containers.

### Scope

The assessment included the following areas:

-   Internal Nmap scanning of the host system and Docker containers

-   Vulnerability assessments using Nessus Essentials

-   Software composition and dependency analysis (SCA)

-   Static application security testing (SAST)

-   Comparative analysis of configuration and exposure differences between the two versions

### Tools Used

The following tools were used during the assessment:

-   **Nmap** -- for network enumeration and port/service fingerprinting

-   **Nessus Essentials** -- for vulnerability scanning

-   **Syft** -- for generating Software Bill of Materials (SBOM)

-   **Grype** -- for vulnerability scanning based on SBOM output

-   **Semgrep** -- for static code analysis and detection of insecure coding practices

### Summary of Assessment Areas

-   **Network and Service Exposure**\
    Evaluation of listening services and ports across containers, identifying exposed services and changes between versions.

-   **Dependency-Level Vulnerabilities**\
    Identification of known vulnerabilities in open-source dependencies using SBOM-based scanning.

-   **Static Code and Application Security**\
    Review of application source code for insecure patterns and misconfigurations using Semgrep.

-   **Comparative Version Analysis**\
    Direct comparison between v3.4.3 and v3.4.5 across all scanned domains to identify improvements, regressions, or unchanged security states.

### 📄 Full Report

[View Full Security Assessment Report (PDF)](https://github.com/jacobrphillips/Security-Research-Project/blob/main/Security%20Research%20Report.pdf)
