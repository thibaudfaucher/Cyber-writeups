# Intro to Cyber Security (TryHackMe)

## Offensive Security Intro
### Tool used: dirb
**What is does:** Scan a website and discover hidden pages and directories.
It automatically tries a large list of common names (admin, login, backup, uploads,...) and tells me which ones actually exist on the server.

**Basic usage:**
dirb http://exemple.com
dirb http://TARGET_IP/

**Notes:**
Only use it on systems I have permission to test

## Defensive Security Intro
**What to do when attacked:**
* Stop the attack
* Create or update the **threat intelligence**: information about attackers and how they operate.
* Submit an incident report: document what happened, how it was detected, and how it was handled)

## Search Tools
* **Shodan:**
a search engine for internet-connected devices (servers, cameras, industrial systems). It shows what is exposed publicly and where.

* **VirusTotal:**
checks a file, URL, domain or hash against many antivirus engines at once, and shows whether any flag it as malicious.

* **Common Vulnerabilities and Exposures (CVE):**
a public catalog of known vulnerabilities, each with a unique ID (e.g. CVE-2021-44228).

* **Linux Manual Pages**
built-in documentation for any Linux command. Usage: `man <command>`
