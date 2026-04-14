# Honeypot-security
Cybersecurity project highlighting an SSH honeypot, attack logging, detection rules, and dashboard. 
*This honeypot is for educational and research purposes only. Do not deploy on production systems.*

## Overview 
This project simulates an SSH (Secure Shell) service to log attacker behavior in a controlled environment.
The honeypot logs login attempts, commands, and session activity, then applies detection rules to categorize attacks(brute force, malware, etc.).
A backend API and dashboard is implemented to visualize the data.

## Architecture
- Honeypot - captures attacker input
- Parser - cleans and analyzes log data
- API - receives events and server data to the dashboard
- Dashboard - displays attacks, stats, and timelines

## Features 
- Fake SSH login prompt
- Command logging
- Timestamps + IP address of the attacker
- Detection rules for attacks
- Real-time dashboard
- Attack classification

## Languages & Frameworks 
- Python (honeypot and parser)
- Node.js (backend)
- MongoDB or PostgreSQL (database)
- React or Next.js (dashboard)

## How It Works 
1. Attacker connects to the honeypot
2. Honeypot logs commands
3. Parser cleans logs and analyzes attacks
4. Data is sent to the backend API
5. Dashboard displays real-time activity

## How to install 

## Screenshots 

## Documentation 
