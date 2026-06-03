# Nmap Notes

## What is Nmap?
Nmap is a network scanning tool used to discover hosts, open ports, and services running on a network.

## Why is it useful?
- Identifies open ports
- Detects running services
- Helps map a network
- Commonly used during reconnaissance

## Basic Scan
nmap 192.168.1.1

Scans a host for open ports.

## Service Version Detection
nmap -sV 192.168.1.1

Attempts to identify service versions running on open ports.

## OS Detection
nmap -O 192.168.1.1

Attempts to detect the operating system.

## What I Learned
- Open ports can expose services to attackers
- Enumeration is an important part of cybersecurity
- Nmap is widely used in penetration testing and security assessments

# Understanding sudo in Linux

## What is sudo?
sudo allows a permitted user to execute commands with elevated privileges, typically as the root user.

## Why is it important?
- Prevents users from constantly logging in as root
- Improves accountability through logging
- Supports the principle of least privilege

## Example
sudo apt update

Runs the command with administrative privileges.

## What I Learned
- Linux separates normal user permissions from administrative privileges
- sudo is safer than operating directly as root