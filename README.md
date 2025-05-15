This Power BI dashboard analyzes streaming content data from Netflix, using a dataset named **`netflix_titles.csv`**. It provides rich insights into content types, genres, country distribution, ratings, and trends over time.

## 📁 Dataset Overview

The dataset contains **8,808 rows** and the following columns:

| Column Name     | Description                                 |
|------------------|---------------------------------------------|
| `show_id`        | Unique ID for each show                     |
| `type`           | Movie or TV Show                            |
| `title`          | Name of the content                         |
| `director`       | Director(s) of the content                  |
| `cast`           | Main cast members                           |
| `country`        | Country of origin                           |
| `date_added`     | Date the show was added to Netflix          |
| `release_year`   | Year the content was released               |
| `rating`         | Age rating (e.g., PG, TV-MA, R)             |
| `duration`       | Duration (minutes for movies, seasons for TV shows) |
| `listed_in`      | Genres/categories                          |
| `description`    | Short summary of the content                |

---

## 📊 Dashboard Features

### 📌 KPIs Displayed:
- **Total Shows**
- **Total Directors**
- **Total Genres (Listed In)**
- **Content Range**: From earliest to latest release year

### 📈 Visual Insights:
- 🎭 **Genres by Total Shows**
- 🎬 **Ratings by Movies**
- 🌍 **Count of Shows by Country**
- 🎥 **Count of Movies vs. TV Shows**
- 📅 **Content Added Over Time (Release Year)**

### 🎛 Filters & Slicers:
- Content Type (Movie / TV Show)
- Country
- Release Year
- Rating
- Genre (Listed In)

---

## 🛠 Skills & Tools Used

- **Power BI Desktop**
- **Power Query** for data cleaning and transformation
- **DAX (Data Analysis Expressions)** for calculated metrics
- **Visual design** and user interactivity in reports

---

## 📂 Project Files

- `netflix_titles.csv` – Source data file  
- `NetflixDashboard.pbix` – Power BI project file
   

---

## 📷 Dashboard Preview

- `Netflix.png` – Result Dashboard 

---
