# Flood Risk Assessment - Nacimiento, Chile

Hydrological and hydraulic analysis of the Biobío and Vergara rivers using Python and open data.

## About
This project replicates the flood risk methodology applied in Nacimiento, Biobío Region, Chile. 
It analyzes flood hazard for return periods of 5, 25, 50 and 100 years using the DEFRA 2006 classification.

## Study Area
- **Ribera Sur Río Biobío:** 85% of the area presents significant to extreme flood hazard
- **Ribera Oriente Río Vergara:** 32.7% of the area presents significant to extreme flood hazard
- **Fundo Los Tralpenes:** outside flood risk for all return periods

## Methods
- Hydrological frequency analysis (Gumbel, Gamma, Normal distributions)
- Manning coefficient determination (Cowan method)
- Flood Hazard Index: HR = d × (v + 0.5) + DF (DEFRA 2006)

## Tools
- Python | GeoPandas | Rasterio | Folium | Matplotlib
- Jupyter Notebook

## Author
Constanza Morales - Geological Civil Engineer  
[LinkedIn](https://linkedin.com/in/) | [GitHub](https://github.com/conimoralesg)
