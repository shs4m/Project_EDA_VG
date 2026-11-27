[README.md](https://github.com/user-attachments/files/35501334/project_readme.md)
# Video Game Sales Analysis (`Project_SDS105`)

An exploratory data analysis (EDA) and statistical study of global video game sales (`vgsales.csv`), examining market trends across platforms, genres, publishers, and geographic regions.

## Project Overview

This repository contains the code, datasets, and visual analyses created for **SDS 105**. The project investigates key questions in the video game industry, such as:
* Which platforms and genres have historically generated the highest global sales?
* How do regional preferences compare across North America (`NA_Sales`), Europe (`EU_Sales`), Japan (`JP_Sales`), and other territories (`Other_Sales`)?
* How have video game release volumes and total sales evolved over time?
* Which publishers dominate specific genres and console generations?

## Repository Structure

```text
Project_SDS105/
├── Project_SDS105_Code.ipynb   # Main Jupyter Notebook with data cleaning, EDA, and visualizations
├── vgsales.csv                 # Primary dataset containing historical video game sales records
├── README.md                   # Project documentation
└── .gitignore                  # Ignores temporary files and Jupyter checkpoints
```

## Dataset Description

The analysis uses `vgsales.csv`, which includes records of video games with sales greater than 100,000 copies. Key variables include:

| Column | Description |
| :--- | :--- |
| `Rank` | Ranking of overall global sales |
| `Name` | Title of the video game |
| `Platform` | Console or platform of release (e.g., Wii, NES, PS4, PC) |
| `Year` | Year of the game's release |
| `Genre` | Genre of the game (e.g., Action, Sports, Role-Playing) |
| `Publisher` | Publisher of the game |
| `NA_Sales` | Sales in North America (in millions) |
| `EU_Sales` | Sales in Europe (in millions) |
| `JP_Sales` | Sales in Japan (in millions) |
| `Other_Sales` | Sales in the rest of the world (in millions) |
| `Global_Sales` | Total worldwide sales (in millions) |

## Getting Started

### Prerequisites
Make sure you have Python 3.8+ and Jupyter Notebook (or JupyterLab / VS Code) installed, along with standard data science libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Running the Analysis
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/shs4m/Project_SDS105.git
   cd Project_SDS105
   ```
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open the main `.ipynb` notebook and run all cells to reproduce the data cleaning steps, summary statistics, and charts.

## Author

* **shs4m** — [GitHub Profile](https://github.com/shs4m)
