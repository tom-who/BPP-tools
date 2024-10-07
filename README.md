## My recon tools for real world engagements

---

# Install:

`git clone https://github.com/tom-who/BPP-tools.git`

`cd BPP-tools`

`chmod +x recon`

`./recon example.com`

# NS

`

**This will only collect indexed urls on google.com, not admin.google.com etc...**

# RECON

**This script is for the wildcard targets, it uses CLI tools and APIs to gather subdomains from the internet, pipes them into a file and gets rid of any dupes
It then checks what subdomains are alive and filters them into their respective status codes**

**Following this it uses the hosts that are alive and uses tools like katana and gau to check for indexed URLS on the internet, this part of the recon has found me XSS in 5 minutes before. Just make sure you know what you are looking for.**
**It also checks for API endpoints and sorts them into their respective files**

# USES

`ns google.com`

`recon google.com`
