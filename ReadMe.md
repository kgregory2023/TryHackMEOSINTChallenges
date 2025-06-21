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

![1](https://github.com/user-attachments/assets/4f752775-7e9e-42e2-a69a-ad39590f1a9e)


### 🌐 Twitter Enumeration:
- Found Twitter handle `@OWoodflint`
- Identified BSSID: `B4:5D:50:AA:86:41`
- Tweet hinted at open WiFi access: “From my house I can get free WiFi ;D”
![2](https://github.com/user-attachments/assets/8ac3a983-cec1-4af8-b590-063bde98e9ba)


### 🌍 Geolocation:
- Input GPS coordinates to map: Located user in the UK region.
![7](https://github.com/user-attachments/assets/3e804588-8207-448b-a445-3e965f028eee)


### 📝 Blog OSINT:
- Discovered [owoodflint.wordpress.com](https://owoodflint.wordpress.com)
- Post says: “I’m in New York right now...”
- Inspected source code: Hidden message found in white font – `pennYDr0pper.!`
![3](https://github.com/user-attachments/assets/9209f969-eb7c-4be6-8936-ad3e15cd895a)
![6](https://github.com/user-attachments/assets/a8651299-1ad0-46c9-8802-7d3331bca68b)



### 💻 GitHub Enumeration:
- GitHub repo: [OWoodfl1nt/people_finder](https://github.com/OWoodfl1nt/people_finder)
- GitHub Bio mentions open source work
- Email found: `OWoodflint@gmail.com`
![4](https://github.com/user-attachments/assets/08862cb8-6028-480d-beeb-5e9fdad900b7)


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
