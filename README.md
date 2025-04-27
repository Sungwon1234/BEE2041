# Premier League Transfer Fees and Player Performance Analysis (2023/24)

## Project Structure
- `2041final.ipynb`:  
  The main Jupyter Notebook file containing:
  - Data collection (FBRef and Transfermarkt)
  - Data cleaning and merging
  - Exploratory data analysis (EDA)
  - Regression analysis (overall and position-specific)
- `data/`:  
  Folder containing raw, transfermarkt_transfer_fees_2023_selenium.csv.
- `PremierLeague_Transfer_Performance_Project/`:  
  Folder containing data, both raw (fbref_player_stats_2023.csv) and processed (merged_full_data.csv, merged_matched_data.csv) 

## How to Run
1. Open `2041final.ipynb` using Jupyter Notebook.
2. Execute each cell sequentially to reproduce the analysis and visualisations.
3. Ensure that the relative paths to data files are correctly maintained.

## Data Sources
- [FBRef](https://fbref.com/en/comps/9/2023-2024/stats/2023-2024-Premier-League-Stats) — Player performance statistics
- [Transfermarkt](https://www.transfermarkt.com/premier-league/transfers/wettbewerb/GB1/plus/?saison_id=2023&s_w=s&leihe=0&intern=0) — Transfer fee data

## Key Libraries Used
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `BeautifulSoup`
- `Selenium`

