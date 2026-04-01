# Netflix Ratings Analysis

Investigating whether Netflix's rapid content expansion came at the cost of audience quality, using IMDb ratings merged with Netflix catalog data.

---

## Getting Started

### 1. Clone the Repository

In RStudio, go to **File → New Project → Version Control → Git** and enter the following:

- **Repository URL:** `https://github.com/athapa2626/Netflix-Ratings-Analysis.git`
- **Project directory name:** `Netflix-Ratings-Analysis`
- **Create project as subdirectory of:** your preferred location (e.g., `~/Documents`)

Then click **Create Project**.

---

### 2. Download the Datasets

Download the following datasets from Kaggle and place them in a `Data/` folder inside the project directory:

| File | Source |
|------|--------|
| `netflix_titles.csv` | [Netflix Shows – Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows) |
| `TMDB_all_movies.csv` | [TMDB Movies Daily Updates – Kaggle](https://www.kaggle.com/datasets/alanvourch/tmdb-movies-daily-updates) |

Your project structure should look like this:
```
Netflix-Ratings-Analysis/
└── Data/
    ├── netflix_titles.csv
    └── TMDB_all_movies.csv
```

---

### 3. Install Required Packages

Run the following **once** in your R console if these packages aren't already installed:
```r
install.packages("dplyr")
install.packages("stringr")
```
