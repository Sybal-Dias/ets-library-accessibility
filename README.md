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
- `data/`: raw and processed datasets
- `src/`: reusable Python code
- `visualizations/`: generated map and bar chart


## Key Findings

- 20% of ETS bus stops are within 1 km of a library.
- West and NW neighborhoods have the least access.
- Map clearly visualizes transit-library access gap.

## How to Run

1. Clone the repo
2. Install requirements: `pip install -r requirements.txt`
3. Run `scripts/ets_library_accessibility.py`
4. Open `visualizations/accessibility_map.html` in your browser
<img width="400" height="370" alt="image" src="https://github.com/user-attachments/assets/0ee3259d-bf9b-49dd-8b2a-75df18668848" />


At the end of the story remember to  run the following command in your bash to savescripts files of the .ipynb
jupyter nbconvert --to script ets_library_main.ipynb