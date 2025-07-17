
# 🏏 IPL 2025 - Live Score & Points Table Dashboard (Power BI)

An interactive Power BI dashboard that visualizes live IPL 2025 match scores, player statistics, and tournament points table in real time.

## 📊 Dashboard Features

### 🔴 Live Score Page
- Real-time score updates for both innings
- Batting and bowling cards with:
  - Player-wise stats (Runs, Strike Rate, Fours, Sixes, Wickets, Economy)
  - Live indicators for currently playing batsmen
- Team summaries with run rate, required rate, and wickets
- Visual KPIs: Twos, Fours, Sixes
- Pie charts showing contribution distribution (sixes, fours, wickets)
- Toggle option for team-wise performance

### 🏆 Points Table Page
- Tournament-wide team performance
- Stats include:
  - Team Name, Captain, Matches Played, Won, Lost, Points, Net Run Rate
- Year filter for season view (e.g., 2025)
- Scrollable list with team logos and captain images

---

## 🔗 Data Source
- Live match data is fetched via cricket APIs (such as [Cricbuzz API via RapidAPI](https://rapidapi.com/apidojo/api/cricbuzz))  
- Updated automatically using Power BI Web connector or Python script

---

## 📁 Project Structure
```
📊 IPL-Live-Score-Dashboard/
│
├── PowerBI_Report.pbix           # Main Power BI dashboard file
├── README.md                     # Project documentation
├── Images/                       # Screenshots and assets
│   ├── LiveScorePage.png
│   └── PointsTablePage.png
└── data/                         # Raw and processed JSON/API data (optional)
```

---

## 🚀 Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/tinkusharma1/IPL_DashBoard
   ```

2. Open `PowerBI_Report.pbix` in Power BI Desktop

3. Replace placeholder API key with your valid cricket data API key

4. Refresh the data and publish to Power BI service if needed

---

## 📸 Screenshots

### 🔴 Live Score Dashboard  
![Live Score](./Images/LiveScorePage.png)

### 🏆 Points Table  
![Points Table](./Images/PointsTablePage.png)

---

## 📌 Technologies Used
- **Power BI Desktop**
- **DAX & Power Query**
- **Cricbuzz API / RapidAPI**
- **JSON / Web Connector**

---

## 👨‍💻 Author
**Teknath**  
[GitHub](https://github.com/tinkusharma1)
