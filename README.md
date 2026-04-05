# Subdomain Enumerator

A Python-based recon tool that discovers active subdomains for a given domain.

## What it does
- Takes a target domain as input
- Tests subdomains from a wordlist against the target
- Detects live servers, redirects, and dead subdomains
- Saves found servers to `Found Servers.txt`

## Requirements
- Python 3.x
- requests library (`pip install requests`)

## Usage
1. Add your wordlist to `third-level-domains.txt` (one subdomain per line)
2. Run the script: `python subdomain_enumerator.py`
3. Enter your target domain when prompted

## Legal Disclaimer
This tool is for educational purposes and authorized testing only. Only use against domains you own or have explicit permission to test. Unauthorized use is illegal.
