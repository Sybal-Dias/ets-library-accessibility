 # Edmonton Transit System (ETS) Bus Stop to Public Library Proximity Analysis 🚌📚

This geospatial project analyzes how **accessible public libraries are via Edmonton Transit Service (ETS) bus stops** by measuring the walking distance from ETS bus stops to nearby libraries, using open geospatial data and *Python tools*.

**Goal**: Identify areas underserved by libraries (bus stops >1 km walking distance away from a public library)  
**Tech**: Jupyter Notebook, python, pandas, geopy, folium, matplotlib  
<img width="500" height="700" alt="image" src="https://github.com/user-attachments/assets/7fe11d5e-1e3d-43ed-98aa-c6f396511f8b" />

## Skills Demonstrated
- Data cleaning, merging & saving output (pandas)
- Geospatial analysis (geopy)
- Data categorization + Interactive Mapping + Visualization (matplotlib, folium, Tableau)
- Mapping underserved areas using public datasets

 ## Data Sources
- [ETS Bus Stops Open Data](https://data.edmonton.ca/)
- [Edmonton Public Libraries Locations](https://data.edmonton.ca/)

## Project Structure
See folder layout for:
project-root/
 - ├── data/
 - │ ├── raw/ # Original datasets
 - │ └── processed/ # Enriched dataset with library distances
 - ├── visualizations/ # HTML map & bar chart image
 - ├── src/ # Python scripts and analysis
 - ├── .gitignore
 - ├── .gitattributes
 - ├── README.md

## Key Findings

- % of ETS bus stops are within 1 km of a library.
- West and NW neighborhoods have the least access.
- Map clearly visualizes transit-library access gap.

## Run in Jupyter Notebook

This project was developed using **Jupyter Notebook** for an interactive experience.

1. Install JupyterLab:
```bash
pip install jupyterlab
```

2. Launch JupyterLab:
```bash
jupyter lab
```

3. Open and run `ets_library_accessibility.ipynb` to explore and visualize the data interactively.
<img width="400" height="370" alt="image" src="https://github.com/user-attachments/assets/0ee3259d-bf9b-49dd-8b2a-75df18668848" />


## 📊 Interactive Tableau Dashboard

Explore an interactive dashboard visualizing:

🗺️ A Map of all ETS bus stops color-coded by distance to the nearest public library

📊 A Bar Chart showing the percentage of stops that are underserved (>1 km from a library)

👉 Click here to view Dashboard on [Tableau Public](https://public.tableau.com/views/ets-bus-stop-library-proximity/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
Built using cleaned data from this project and visualized with latitude, longitude, and categorized access data. 
