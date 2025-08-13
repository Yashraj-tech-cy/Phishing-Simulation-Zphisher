# Phishing Page Simulation using Zphisher

Project Overview
This project demonstrates a **phishing page simulation** for **educational and cybersecurity awareness purposes**.  
The tool used is **Zphisher**, a penetration testing tool that can simulate phishing pages for platforms like Instagram, Facebook, and Google.

**Disclaimer:**  
This project was conducted using a **dummy account** only.  
It is intended **solely for research and training purposes**.  
Misuse of phishing tools against real accounts is **illegal**.

 Tools & Technologies
- **Google Cloud Shell**
- **Zphisher** (GitHub: [https://github.com/htr-tech/zphisher](https://github.com/htr-tech/zphisher))
- **Cloudflared** for public URL hosting
- Dummy account for safe testing


Steps Followed

1 Cloning Zphisher Repository
```bash
git clone https://github.com/htr-tech/zphisher.git
cd zphisher
chmod +x *
```
2 Running Zphisher
```bash
bash zphisher.sh
```
- Selected Instagram Traditional Login Page option.

- Chose Cloudflared hosting.

- Used default port and default mask URL.
3 Generating the Phishing Link
Zphisher generated a Cloudflared public URL.

This URL was opened in Incognito mode.

4 Testing with Dummy Account
- Entered dummy credentials into the simulated phishing page.
- Observed credentials captured in the Cloud Shell terminal.
Entered dummy credentials into the simulated phishing page.

Observed credentials captured in the Cloud Shell terminal.
