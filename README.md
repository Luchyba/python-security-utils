# python-security-utils
This script includes a Port Scanner and a WHOIS Lookup tool, designed for use in your virtualized lab environment.
Project Overview
This repository contains a collection of Python-based utilities designed to automate early-stage security reconnaissance and network auditing. Developed as part of my MSc in Advanced Computer Security, these tools focus on transitioning from manual command-line tasks to automated, scriptable workflows.

Key Features
Automated WHOIS Lookup: Rapidly gather administrative and registration data for target domains.

Socket-Based Port Scanner: A multi-threaded utility to identify open services on a target host.

Network Service Identification: Basic banner grabbing to identify service versions and potential vulnerabilities.

Modular Authentication: A clean implementation of secure user login logic for integration into larger security applications.

Technical Stack
Language: Python 3.x

Libraries: socket, sys, whois, threading

Environment: Optimized for Linux (Kali/Ubuntu) virtualized penetration testing labs.

Why This Project?
The goal of this toolkit is to provide a lightweight, dependency-minimal alternative to heavy security suites. By building these from scratch, I aim to deepen my understanding of low-level network protocols and how Python interacts with system-level sockets.

Future Roadmap
[ ] Integration with Scapy for advanced packet manipulation.

[ ] Exporting scan results to JSON/CSV for SIEM (Splunk) ingestion.

[ ] Adding a basic GUI using Tkinter for educational demonstrations
