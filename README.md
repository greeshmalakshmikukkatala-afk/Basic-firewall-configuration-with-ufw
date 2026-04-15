# Basic-firewall-configuration-with-ufw
UFW: A simple command-line firewall tool used to manage and secure network traffic by allowing or blocking connections.
# Basic Firewall Configuration with UFW
## Introduction
UFW (Uncomplicated Firewall) is an easy-to-use tool for managing firewall rules in Linux systems. It helps secure your system by controlling incoming and outgoing network traffic.
## Installation
To install UFW, run:
sudo apt install ufw
## Enable Firewall
To enable UFW:
sudo ufw enable
## Disable Firewall
To disable UFW:
sudo ufw disable
## Check Status
To check firewall status:
sudo ufw status
## Basic Rules
### Allow a Port
Allow HTTP (port 80):
sudo ufw allow 80
### Deny a Port
Block SSH (port 22):
sudo ufw deny 22
### Allow a Service
Allow SSH:
sudo ufw allow ssh
### Delete a Rule
Remove allowed port:
sudo ufw delete allow 80
## Default Policies
### Block Incoming Traffic
sudo ufw default deny incoming
### Allow Outgoing Traffic
sudo ufw default allow outgoing
# Update system
sudo apt update
# Install UFW
sudo apt install -y ufw
# Allow SSH
sudo ufw allow ssh
# Deny HTTP
sudo ufw deny http
# Enable firewall
sudo ufw  enable
# Show status
sudo ufw status verbose
## Conclusion
UFW provides a simple and effective way to manage firewall rules and improve system security with minimal effort.
