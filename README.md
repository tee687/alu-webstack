# ALU Webstack HTTPS SSL Project

## Project Overview
This project sets up HTTPS/SSL termination for the web application stack using HAProxy, Certbot, and custom Bash auditing scripts.

## Tasks
* **0. World Wide Web**: Bash script to inspect domain DNS A records for target subdomains (`www`, `lb-01`, `web-01`, `web-02`).
* **1. HAProxy SSL Termination**: HAProxy configuration to terminate HTTPS traffic on port 443 and forward requests to backend web servers.

## Requirements
* All scripts executed on Ubuntu 16.04 LTS environments.
* Compliant with ShellCheck standards.
