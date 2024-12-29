# Spotify-Themed Flexdashboard 🎵

## Overview
This **Spotify-Themed Flexdashboard** provides an interactive visualization and analysis of Spotify's most-streamed songs dataset. The dashboard is designed with a sleek **black and green theme**, reflecting Spotify's branding, and features detailed insights into the trends, artists, and songs that dominate the music streaming platform. 

The dashboard is built using **R Flexdashboard** and leverages powerful libraries like **ggplot2**, **highcharter**, and **DT** for data visualization and interactivity.

---

## Features

### 🏠 Home Page
- **Spotify Logo & Theme**: A visually appealing interface inspired by Spotify's design.
- **Introduction Video**: Embedded video providing an introduction to Spotify.
- **Popular Songs Links**: Direct links to top Spotify playlists, including Today’s Top Hits and Global Songs.

### 📊 Dashboard
- **Value Boxes**: Highlight key statistics such as the top artist, most-streamed song, and total streams.
- **Visualizations**:
  - **Bar Chart**: Top 10 artists by total streams.
  - **Line Chart**: Yearly trends in streaming data.
  - **Pie Chart**: Distribution of genres or playlists.
- **Dynamic Charts**: Built using `ggplot2` and `highcharter` for interactive exploration.

### 📈 Data Analysis
- **Statistical Insights**: Detailed analysis of trends, distributions, and relationships within the dataset.
- **Visual Exploration**: Histograms, scatter plots, and trend lines to uncover patterns in energy, danceability, and more.

### 📂 Raw Data
- **Interactive Table**: Explore the complete dataset using the `DT` library for sorting, filtering, and exporting.

---

## Technologies Used
- **R Flexdashboard**: To create a responsive, multi-page dashboard.
- **ggplot2**: For advanced data visualizations.
- **highcharter**: For interactive charts.
- **DT**: For interactive and user-friendly data tables.
- **CSS**: Custom styling for a Spotify-inspired design.

---

## How to Use
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/spotify-flexdashboard.git
   ```
2. Open the `.Rmd` file in **RStudio**.
3. Install the required R packages:
   ```R
   install.packages(c("flexdashboard", "ggplot2", "highcharter", "DT"))
   ```
4. Knit the RMarkdown file to render the dashboard.
5. Open the rendered HTML file in your web browser.

---

## Dataset
The dataset used in this project is sourced from Spotify and contains:
- Song details: Title, artists, release dates, and streams.
- Audio features: Danceability, energy, valence, etc.
- Metadata: Playlist and chart appearances.

---

## Preview

![Screenshot 2024-12-29 173353](https://github.com/user-attachments/assets/ca00a8f6-16c7-4ec0-83f6-1169e5106926)
![image](https://github.com/user-attachments/assets/3b695624-5773-4762-b215-b34e2010e8ef)

---

