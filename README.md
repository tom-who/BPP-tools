# Recon Script for Bug Bounty

## Overview
This script automates reconnaissance for bug bounty hunting. It performs subdomain enumeration, URL gathering, and basic vulnerability scanning for a specified domain. Built with several popular CLI tools, this script simplifies the initial stages of web application security testing.

## Features
- **Subdomain Enumeration**: Gathers subdomains using various tools and APIs.
- **URL Gathering**: Extracts interesting URLs from the target domain.
- **Filtering**: Identifies responsive subdomains and categorizes them based on HTTP response codes.
- **Title Extraction**: Retrieves page titles from active URLs for better insight.
- **Screenshots**: Generates screenshots of live subdomains with Aquatone (if configured).

## Prerequisites
Before running the script, ensure you have the following tools installed:
- [subfinder](https://github.com/projectdiscovery/subfinder)
- [assetfinder](https://github.com/tomnomnom/assetfinder)
- [httpx](https://github.com/projectdiscovery/httpx)
- [katana](https://github.com/projectdiscovery/katana)
- [aquatone](https://github.com/michenriksen/aquatone)
- [jq](https://stedolan.github.io/jq/)
- [curl](https://curl.se/)

You can install the tools using your package manager or from the respective repositories.

## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/tom-who/BPP-tools.git
   cd BPP-tools
   chmod +x recon; chmod +x ns

   ./recon example.com
   ./ns example.com (no subdomain gathering)
