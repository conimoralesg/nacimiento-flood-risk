# Flood Risk Assessment - Nacimiento, Chile

Hydrological and hydraulic analysis of the Biobío and Vergara rivers using Python and open data.

## About

This project replicates the flood risk methodology applied in Nacimiento, Biobío Region, Chile.
It analyzes flood hazard for return periods of 5, 25, 50 and 100 years using the DEFRA 2006 classification.

## Key Results

- **South Bank Biobío River:** 85% of the area presents significant to extreme flood hazard
- **East Bank Vergara River:** 32.7% of the area presents significant to extreme flood hazard
- **Fundo Los Tralpenes:** outside flood risk for all return periods studied
- Average hazard: 47% extreme, 35% significant, 2.5% moderate
- 200 people (0.7% of total population) exposed to flood risk

## Interactive Map

[View flood risk zones map](notebooks/nacimiento_flood_map.html)

## Data Sources

- Flow rates: DGA Station Río Biobío en Coihue (1983–2019)
- Hazard classification: DEFRA 2006 methodology
- Commune boundary: FAO GAUL 2015
- Satellite imagery: Esri World Imagery via Google Earth Engine

## Tools

- Python | GeoPandas | Rasterio | Geemap | Google Earth Engine | Matplotlib
- Jupyter Notebook

## Author

Constanza Morales - Geological Civil Engineer  
[LinkedIn](https://linkedin.com/in/constanza-morales-gajardo) | [GitHub](https://github.com/conimoralesg)
