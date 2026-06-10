# IPL Stats Analysis with Matplotlib

A cricket analytics project built using Python, Pandas, NumPy, and Matplotlib to analyze Indian Premier League (IPL) ball-by-ball and match-level data.

The project focuses on data cleaning, aggregation, statistical analysis, and visualization to uncover insights about batting performances, bowling records, strike rates, venue usage, and player consistency across IPL seasons.

---

## Dataset

The project uses two datasets:

* `deliveries.csv` – Ball-by-ball IPL data
* `matches.csv` – Match-level IPL data

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib

---

## Data Preprocessing

Before analysis, the following cleaning steps were performed:

* Handled missing values
* Standardized IPL franchise names:

  * Royal Challengers Bangalore → Royal Challengers Bengaluru
  * Kings XI Punjab → Punjab Kings
  * Delhi Daredevils → Delhi Capitals
  * Rising Pune Supergiant → Rising Pune Supergiants
* Standardized season values
* Merged match-level and ball-by-ball datasets for season-wise analysis

---

## Analysis and Visualizations

### 1. Top Run Scorers in IPL History

Calculated total runs scored by every batter and visualized the top 10 run scorers.

**Visualization:** Bar Chart

**Insights:**

* Identifies the most successful IPL batters.
* Highlights long-term consistency and longevity.

---

### 2. Highest Individual Scores

Calculated runs scored by each batter in every match and identified the top 10 highest individual innings.

**Visualization:** Annotated Bar Chart

**Insights:**

* Reveals the greatest batting performances in IPL history.
* Compares elite innings across different players.

---

### 3. Leading Wicket Takers

Calculated wickets taken by bowlers while excluding run-out dismissals.

**Visualization:** Horizontal Bar Chart

**Insights:**

* Shows the most successful wicket-taking bowlers.
* Highlights bowlers with sustained IPL success.

---

### 4. Runs vs Strike Rate Analysis

Calculated strike rates using:

Strike Rate = (Runs ÷ Balls Faced) × 100

Wides were excluded while calculating balls faced.

**Visualization:** Scatter Plot with Color Mapping

**Insights:**

* Compares scoring ability with scoring speed.
* Helps identify aggressive batters and consistent run scorers.
* Reveals players who balance volume scoring with high strike rates.

---

### 5. Virat Kohli Match-by-Match Performance

Analyzed Virat Kohli's runs in every IPL innings.

**Visualization:** Line Plot

**Insights:**

* Shows consistency throughout his IPL career.
* Highlights peaks and fluctuations in performance.

---

### 6. Rohit Sharma Season-Wise Runs

Calculated Rohit Sharma's total runs in each IPL season.

**Visualization:** Line Plot

**Insights:**

* Tracks batting performance across seasons.
* Highlights strong and weak years.

---

### 7. Virat Kohli Season-Wise Runs

Calculated Virat Kohli's total runs in each IPL season.

**Visualization:** Line Plot

**Insights:**

* Shows long-term consistency.
* Identifies peak scoring seasons.

---

### 8. Virat Kohli vs Rohit Sharma Comparison

Compared season-wise runs of two IPL legends.

**Visualization:** Multi-Line Chart

**Insights:**

* Direct comparison of batting performances across seasons.
* Highlights differences in consistency and peak years.

---

### 9. Venue Analysis

Analyzed the number of IPL matches hosted at each venue.

**Visualization:** Pie Chart

**Insights:**

* Identifies the most frequently used IPL stadiums.
* Groups less frequently used venues into an "Others" category.

---

### 10. Strike Rate Distribution

Analyzed the overall distribution of batter strike rates.

**Visualization:** Box Plot

**Insights:**

* Displays median strike rate.
* Shows spread and variability.
* Detects outliers and exceptionally aggressive batters.

---

### 11. Multi-Player Seasonal Dashboard

Created a dashboard comparing season-wise runs of:

* Rohit Sharma
* Virat Kohli
* MS Dhoni
* Manish Pandey

**Visualization:** 2×2 Subplot Dashboard

**Insights:**

* Enables side-by-side comparison of batting careers.
* Highlights seasonal trends and consistency.

---

## Key Metrics Used

### Total Runs

Sum of all runs scored by a batter.

### Balls Faced

Calculated by excluding wides.

### Strike Rate

(Runs ÷ Balls Faced) × 100

### Wickets

Calculated using dismissal records while excluding run-outs.

---

## Skills Demonstrated

* Data Cleaning
* Data Aggregation
* GroupBy Operations
* Dataset Merging
* Cricket Analytics
* Exploratory Data Analysis (EDA)
* Statistical Analysis
* Data Visualization
* Matplotlib Plot Customization

---

## Future Improvements

* Orange Cap Analysis by Season
* Purple Cap Analysis by Season
* Team Win Percentage Analysis
* Toss Impact Analysis
* Venue-Wise Player Performance
* Batter vs Bowler Matchup Analysis
* Interactive Dashboard Development

---

## Author

Ashwak Kattubadi

GitHub Repository:
https://github.com/Ashwakkattubadi/ipl-stats-matplotlib
