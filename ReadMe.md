# TryHackMe - OhSINT Room 🕵️‍♂️  
**Category:** Open Source Intelligence (OSINT)  
**Platform:** TryHackMe  
**Link:** [https://tryhackme.com/room/ohsint](https://tryhackme.com/room/ohsint)  
**Tools Used:** ExifTool, Google, GitHub, WordPress, Twitter, Maps, Browser Dev Tools

## 🧠 Objective
Use OSINT techniques to discover information from a single image file and trace the target’s online identity across multiple platforms.

---

## 🔍 Walkthrough Summary

### 📸 Metadata Extraction:
Used `exiftool` on `WindowsXP.jpg` to gather GPS metadata:
- **Latitude**: `54° 17' 41.27" N`
- **Longitude**: `2° 15' 1.33" W`
- Image credited to **OWoodflint**

### 🌐 Twitter Enumeration:
- Found Twitter handle `@OWoodflint`
- Identified BSSID: `B4:5D:50:AA:86:41`
- Tweet hinted at open WiFi access: “From my house I can get free WiFi ;D”

### 🌍 Geolocation:
- Input GPS coordinates to map: Located user in the UK region.

### 📝 Blog OSINT:
- Discovered [owoodflint.wordpress.com](https://owoodflint.wordpress.com)
- Post says: “I’m in New York right now...”
- Inspected source code: Hidden message found in white font – `pennYDr0pper.!`

### 💻 GitHub Enumeration:
- GitHub repo: [OWoodfl1nt/people_finder](https://github.com/OWoodfl1nt/people_finder)
- GitHub Bio mentions open source work
- Email found: `OWoodflint@gmail.com`

---

## 🧩 Skills Demonstrated
- Metadata analysis using `ExifTool`
- Correlating usernames across platforms
- Social media footprinting
- Analyzing hidden HTML source
- Passive WiFi reconnaissance from BSSID
- Recon chaining and logical deduction

---

## 🏁 Result
Identified the individual behind the alias `OWoodflint`, mapped their activity geographically, and discovered cross-platform identities using OSINT.
