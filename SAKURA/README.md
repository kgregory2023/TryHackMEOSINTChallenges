
# 🌸 TryHackMe: Sakura Room — OSINT Challenge 

This challenge explores a range of IMINT/GEOINT (Image and Geospatial Intelligence) techniques used in OSINT investigations. Below is a step-by-step breakdown of how each image was analyzed and what clues were derived from them.

---

## 🖼️ Image Analysis Breakdown

### ✈️ Image 1: Airline Logo (JAL)

![JAL Logo](images/jal-logo.png)

- **What we see**: A gold crane logo with the letters `JAL`.
- **Clue derived**: This is the logo of **Japan Airlines**.
- **Usefulness**: Confirms the location is in Japan, likely near or inside an airport.

---

### 🛋️ Image 2: JAL First Class Lounge Signage

![JAL Lounge](images/jal-lounge.png)

- **What we see**: "Tokyo International Airport (Haneda) — JAL First Class Lounge"
- **Clue derived**: This confirms the photo was taken at **Haneda Airport** in **Tokyo, Japan**.
- **Verification**: A quick Google search with the phrase validates the lounge exists in this airport.

---

### 🌍 Image 3: Map Coordinates

![Lake Inawashiro](images/lake-inawashiro.png)

- **Coordinates**: `37.478557, 140.085676`
- **Clue derived**: This points to **Lake Inawashiro**, located in **Fukushima, Japan**.
- **Tools used**: Google Maps – reverse lookup of coordinates to confirm location.

---

### 🌸 Image 4: Cherry Blossom Path & Monument

![DC Blossoms](images/dc-blossoms.png)

- **What we see**: Pink cherry blossom trees and the **Washington Monument** in the background.
- **Clue derived**: This image was taken in **Washington, D.C.**, likely near the **Tidal Basin**.
- **Technique**: Visual landmark recognition confirmed with Google Street View.

---

### 🗺️ Image 5: Google Maps Driving Route

![DC Route](images/washington-monument-to-airport.png)

- **Route**: From the **Washington Monument** to **Ronald Reagan Washington National Airport**.
- **Clue derived**: Validates proximity of landmarks and supports the accuracy of previous image locations.
- **Technique**: Real-time route planning in Google Maps.

---

## 🧠 Techniques Used

- 🔍 **Reverse Image Search** (Google, Yandex)
- 🧾 **Context Clue Analysis** (Text signs, brands, monuments)
- 🌐 **Geolocation** (Google Maps, satellite view)
- 📷 **Landmark Recognition**
- 🗃️ **Metadata Inference**
