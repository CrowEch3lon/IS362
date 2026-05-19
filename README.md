# IS 362: Jupyter Notebook Assignments
### CUNY | Spring 2026 | Daniel Foulen

Updated as of May 13th, 2026
---

## Final Project

**Neighborhood Class, Transit Access, and COVID-19 Outcomes in New York City**

See [`Final Project/`](./Final%20Project/) for notebooks, data, and full documentation.

Interactive notebooks via GitHub Pages:
- [Part 1 — Data Pipeline](https://crowech3lon.github.io/IS362/Final%20Project/DanielFoulen_IS362_FinalProject_Pt1.html)
- [Part 2 — Analysis & Map](https://crowech3lon.github.io/IS362/Final%20Project/DanielFoulen_IS362_FinalProject_Pt2.html)

---

## Setup

Python 3.14. Virtual environment named `IS362` at the repo root.

```bash
python3 -m venv IS362
source IS362/bin/activate
pip install geopandas pandas numpy matplotlib seaborn folium \
            libpysal esda adjustText requests python-dotenv rise
```

Open `IS362.code-workspace` in VSCode and select the **IS362** kernel in any notebook. No manual kernel registration needed.

The Final Project requires a Census API key in a `.env` file at the repo root:

```
CENSUS_API_KEY=your_key_here
```

Keys are free at https://api.census.gov/data/key_signup.html. The `.env` is gitignored.

---