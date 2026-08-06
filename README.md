# Spotify Music & Streaming Analytics Dashboard

## 📌 Overview
This project features an interactive **Power BI Dashboard** that provides data-driven insights into music streaming trends, artist performances, user listening habits, and track popularity metrics using Spotify dataset analytics.

The repository contains the core report files, data models, visual layout configurations, and custom visual themes required to build and render the dashboard.

---

## 📁 Repository & File Structure
The project files inside the Power BI source structure include:

* **`DataModel`**: Defines the underlying data relationships, calculated tables, custom measures, and schema used across the report.
* **`Report/Layout`**: Contains the spatial configuration, tab definitions, and visual object properties for all dashboard pages.
* **`Report/StaticResources/`**: Stores visual assets, including icons (`spotify-logo.png`) and custom color theme templates (`BaseThemes/CY26SU07.json`).
* **`Settings` & `Metadata`**: System configuration files managing report properties, versioning, data source bindings, and privacy levels.

---

## 📊 Key Features & Analysis
* **Track & Artist Performance**: Analyze top-streamed songs, top-charting artists, and popular albums over time.
* **Audio Features Analysis**: Insights into track characteristics such as energy, danceability, tempo, acousticness, and valence.
* **Custom Theme Design**: Enhanced user interface featuring tailored Spotify brand aesthetics and custom report theme files.
* **Interactive Filtering**: Dynamic filtering by genre, release year, artist, and streaming metrics.

---

## 🛠️ Tools & Technologies Used
* **Power BI Desktop**: For report design, visual creation, and DAX calculations.
* **Power Query**: Data cleaning, transformation, and shaping.
* **DAX (Data Analysis Expressions)**: Custom measures for key performance indicators (KPIs) and dynamic aggregation.
* **JSON / Theme Customization**: Custom color palette matching Spotify branding.

---
## 💡 Key Dashboard Insights

### 1. Most Songs Have Low Plays (The Long Tail Effect)
* **What the Data Shows:** More than **75% of songs** fall into the **Low** (260,000 songs) or **Niche** (170,000 songs) categories. Mainstream global **Hits** make up less than 1% of the catalog.
* **Why It Matters:** Most songs on music streaming platforms are undiscovered or created by independent artists. Recommendation engines must continuously surface these hidden tracks alongside top hits to keep users discovering new music.

### 2. Specialized & Regional Genres Have Loyal Listeners
* **What the Data Shows:** Sub-genres and regional music styles—like **World Music**, **Turkish**, and **Techno**—score higher in average popularity than general mainstream tracks.
* **Why It Matters:** Fans of specific regional sounds or sub-cultures are highly dedicated and listen repeatedly. Streaming platforms can drive high user retention by building curated, targeted playlists for these niche audiences.

### 3. Most Music is Clean and Family-Friendly
* **What the Data Shows:** Over **91%** (521,000) of all tracks are clean/non-explicit, while only **8.55%** (49,000) contain explicit content.
* **Why It Matters:** A clean library is universally accessible for public playback in stores, radio broadcasts, and child-safe playlists, maximizing overall streaming potential.

### 4. Every Genre Has Its Own Musical "DNA"
* **What the Data Shows:** Audio attributes directly reflect how music is used:
  * **Comedy:** High in **Speechiness** and **Acousticness** due to spoken dialogue.
  * **Dance Music (Salsa, Samba, Pagode):** High in **Danceability** and **Energy** to keep people moving.
  * **Children's Music:** High in **Danceability** and positive mood (**Valence**).
* **Why It Matters:** Streaming services can automatically analyze audio features to categorize and recommend songs instantly without relying solely on manual genre tags.
* 
## 🚀 How to Open and Use
1. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/Vijay96k1214/Spotify-Insightes-Dashboard.git](https://github.com/Vijay96k1214/Spotify-Insightes-Dashboard.git)
2. Dashboard Image :
<img width="1167" height="656" alt="Screenshot 2026-08-06 111751" src="https://github.com/user-attachments/assets/ea235b7a-f33b-4b39-a491-026c932bc710" />
3. Raw Dataset :
   [Download Raw Dataset] - (https://github.com/Vijay96k1214/Spotify-Insightes-Dashboard/raw/refs/heads/main/dataset.csv)
