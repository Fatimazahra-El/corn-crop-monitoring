# corn-crop-monitoring
NDVI and irrigation monitoring tool using satellite data (Google Earth Engine)
## Features
- NDVI calculation for crop health monitoring  
- NDVI anomalies compared to 10-year historical data  
- Rainfall analysis using CHIRPS daily data  
- Crop coefficient (Kc) and crop evapotranspiration (ETc) calculation  
- Interactive charts and maps for data visualization  

---

## Technologies Used
- **Google Earth Engine** (JavaScript API)  
- **Satellite Imagery**: Sentinel-2, USDA Cropland Data Layer (CDL)  
- **Climate Data**: CHIRPS (rainfall), GRIDMET (ET0)  
- **Visualization**: GEE UI Charts, maps with NDVI/Kc/ETc layers  

---

## How It Works
1. Identify corn fields using USDA Cropland Data Layer (CDL).  
2. Filter Sentinel-2 images for the 2024 growing season and remove clouds.  
3. Calculate NDVI and compare to historical NDVI for anomalies.  
4. Extract daily rainfall data for the farm area.  
5. Calculate Kc using NDVI and ETc using GRIDMET data.  
6. Visualize NDVI trends, rainfall, Kc, ETc, and monthly irrigation needs using charts and maps.  

---



**ETc / Irrigation Map**  
![ETc Chart](screenshots/etc_chart.png)
