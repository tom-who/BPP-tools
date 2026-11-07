# Recon Script for Bug Bounty

## Overview
This script automates reconnaissance for bug bounty hunting. It performs subdomain enumeration, URL gathering, and basic vulnerability scanning for a specified domain. Built with several popular CLI tools, this script simplifies the initial stages of web application security testing.

## software
- [subfinder](https://github.com/projectdiscovery/subfinder)
- [assetfinder](https://github.com/tomnomnom/assetfinder)
- [httpx](https://github.com/projectdiscovery/httpx)
- [katana](https://github.com/projectdiscovery/katana)
- [aquatone](https://github.com/michenriksen/aquatone)
- [jq](https://stedolan.github.io/jq/)
- [curl](https://curl.se/)

## Usage
   ```bash
   git clone https://github.com/tom-who/BPP-tools.git
   cd BPP-tools
   chmod +x recon; chmod +x ns

   ./recon example.com
   ./ns example.com (no subdomain gathering)
```

# Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request.

# Acknowledgements

Thanks to the developers of the tools integrated into this script.
Inspired by various bug bounty methodologies and tools.
