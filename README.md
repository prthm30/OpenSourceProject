The Open Source Audit: Apache HTTP Server

Author: Pratham Choubey
Registration Number: 24BCE10709
Course: Open Source Software
Slot: B22

Project Overview

This repository contains the practical shell scripting component of the "Open Source Audit" Capstone Project. The purpose of these scripts is to demonstrate practical Linux skills, including system administration, file auditing, and automation, reflecting the philosophy of open-source software transparency and flexibility.

The chosen software for this audit is the Apache HTTP Server.

Included Scripts

All scripts are written in bash and are designed to run on a standard Linux environment.

1_system_identity.sh: A script that introduces the Linux system, displaying the OS distribution, kernel version, current user, uptime, and licensing information.
2_package_inspector.sh: Checks if the Apache HTTP Server (apache2) is installed on the system, retrieves its package details, and outputs a brief philosophical note based on the software using a case statement.
3_disk_auditor.sh: Iterates through critical system directories (and the Apache configuration directory) to report disk usage, ownership, and permissions.
4_log_analyzer.sh: Analyzes a provided log file line-by-line to count occurrences of a specific keyword (defaults to "error") and outputs the last 5 matching lines.
5_manifesto_generator.sh: An interactive script that asks the user three questions about their open-source values and generates a personalized text file (manifesto_<username>.txt).
How to Run the Scripts

To execute these scripts on a Linux machine, you must first grant them execute permissions. Open your terminal and run:

chmod +x *.sh
