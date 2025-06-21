# 🛰️ TryHackMe: Searchlight IMINT — OSINT Walkthrough

**Platform**: [TryHackMe](https://tryhackme.com/room/searchlightosint)  
**Category**: OSINT / IMINT / GEOINT  
**Level**: Beginner to Intermediate  
**Author**: Kieren Gregory

## 🧠 Objective

This room introduces the fundamentals of **IMINT (Image Intelligence)** and **GEOINT (Geospatial Intelligence)**. The goal is to extract location and identity information from photos and videos using open-source tools and techniques.

---

## 🧰 Tools Used

- Google Maps / Street View  
- Google Dorking  
- Yandex & Google Reverse Image Search  
- Wikipedia & metadata sources  
- Visual context analysis  
- Basic FFmpeg (for video frame extraction)

---

## ✅ Task Breakdown

### 🏙️ Task 2: Basic Visual Recognition  
**Question**: What street is shown?  
- **Answer**: `Carnaby Street`  
- Used visual context from photo to search for matching architecture.

---

### 🚇 Task 3: Tube Station Investigation  
- **City**: `London`  
- **Station**: `Piccadilly Circus`  
- **Opened**: `10 March 1906`  
- **Platforms**: `4`  
> Matched station name with architecture using Google Maps and Wikipedia.

---

### ✈️ Task 4: Airport Clue  
- **Building**: Vancouver International Airport  
- **Country**: Canada  
- **City**: Richmond  
> Googled “YVR Connects” and verify terminal using interior images.

---

### ☕ Task 5: Coffee Shop Challenge (Scotland)  
- **City**: `Blairgowrie`  
- **Street**: `Allan Street`  
- **Name**: `The Wee Coffee Shop`  
- **Phone**: `+447878839128`  
- **Email**: Found via Facebook  
- **Owner Surname**: `Cochrane`  
> Used storefront locator + Google Street View to match location.

---

### 🥪 Task 6: Restaurant Reverse Image  
- **Restaurant**: `Katz's Deli`  
- **Editor Name**: `Andrew Knowlton`  
> Used Google Reverse Image Search and article matching to ID restaurant and related story.

---

### 🦌 Task 7: Statue Identification  
- **Name**: `Rudolph the Chrome-Nosed Reindeer`  
- **Photographer**: `Kjersti Stensrud`  
> OSINT search across photo registries and art catalogs.

---

### ⚖️ Task 8: Lady Justice Statue  
- **Statue**: `Lady Justice`  
- **Location**: `Alexandria, Virginia`  
- **Opposite Building**: `The Westin Alexandria Old Town`  
> Reverse image + video frame analysis Google Street View.

---

### 🎥 Task 9: Video Geolocation  
- **Clue**: “Riverside Point” sign  
- **Location**: `Novotel Singapore Clarke Quay`  
> Used static frame capture + map triangulation to locate video scene.

---

## 🔍 Key Takeaways

- 📍 **Reverse Image Search** (especially Yandex) is crucial for IMINT.
- 🗺️ **Google Maps Street View** helps match structures from angles.
- 🔢 **Metadata + visual inference** = effective cross-validation.
- 📹 **Screenshots from video** often replace the need for extraction tools like FFmpeg.
