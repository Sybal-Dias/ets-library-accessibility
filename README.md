# ets-library-accessibility
This project demonstrates data-driven urban analysis to improve public services. The methodology can be adapted for other cities and amenities (e.g: childcares, hospitals, schools, etc).

 # Edmonton Transit System (ETS) Bus Stop to Public Library Proximity Analysis 🚌📚

This geospatial project analyzes how **accessible public libraries are via Edmonton Transit Service (ETS) bus stops** by measuring the walking distance from ETS bus stops to nearby libraries, using open geospatial data and *Python tools*.

**Goal**: Identify areas underserved by libraries (bus stops >1 km walking distance away from a public library)  
**Tech**: Jupyter Notebook, python, pandas, geopy, folium, matplotlib  


## Skills Demonstrated
- Data cleaning, merging & saving output (pandas)
- Geospatial analysis (geopy)
- Data categorization + Interactive Mapping + Visualization (matplotlib, folium)
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
3. Run `src/ets_library_accessibility.py`
4. Open `visualizations/accessibility_map.html` in your browser


At the end of story remember to  run the following command in your bash to savescripts files of the .ipynb
jupyter nbconvert --to script ets_library_main.ipynb
