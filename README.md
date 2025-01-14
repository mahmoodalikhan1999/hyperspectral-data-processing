

# **Satellite Imagery Shapefile to CSV Converter**

This repository provides a Jupyter Notebook designed for processing geospatial and hyperspectral data to extract pixel values and coordinates within defined polygon areas. The tool combines information from shapefiles and hyperspectral images to generate comprehensive CSV files suitable for land-use analysis, environmental monitoring, or solar panel site assessments.

---

## **Key Features**
- **Geospatial Data Processing:** Efficiently reads hyperspectral TIFF images and shapefiles to analyze land characteristics.
- **Pixel Data Extraction:** Retrieves pixel values and coordinates within polygons defined in shapefiles.
- **CSV Generation:** Combines shapefile properties, geographic coordinates, and spectral band data into a structured CSV output.
- **Customizable Analysis:** Suitable for diverse applications, including barren land assessment and solar energy suitability studies.

---

## **Getting Started**

### **Prerequisites**

Ensure you have the following Python libraries installed:

```bash
pip install geopandas rasterio shapely fiona numpy pandas
```

### **Input Requirements**
- **Hyperspectral Image:** GeoTIFF file containing multi-band imagery data (e.g., `GoogleEarth_image_with_L_Band.tif`).
- **Shapefile:** Vector data defining polygons for the areas of interest (e.g., `barren.shp`).

---

## **Usage Instructions**

1. **Clone the Repository**
   ```bash
   git clone https://github.com/mahmoodalikhan1999/hyperspectral-data-processing
   cd Satellite_Imagery_Shapefile_to_CSV
   ```

2. **Prepare Input Files**
   - Place the required hyperspectral image and shapefile in the project directory.

3. **Run the Jupyter Notebook**
   - Open and execute `CSVs_Generator.ipynb` in Jupyter Notebook or JupyterLab.

4. **Specify Parameters**
   - Customize file paths and processing parameters as needed.

5. **Generate CSV**
   - The output CSV (e.g., `barren.csv`) will be saved in the specified directory.

---

## **Example Workflow**
1. **Load Hyperspectral Data:**  
   Reads and visualizes the spectral data from the TIFF image.
   
2. **Define Polygon Areas:**  
   Extracts pixel data within polygon regions specified in the shapefile.

3. **Generate CSV File:**  
   Outputs comprehensive data, including coordinates, spectral values, and polygon properties.

---

## **Applications**
- **Land Use Analysis:** Evaluate land characteristics for urban planning and environmental studies.
- **Solar Panel Assessment:** Analyze barren land for solar energy suitability.
- **Environmental Monitoring:** Track changes in land cover and usage over time.

---

## **Dependencies**
- `geopandas`
- `rasterio`
- `shapely`
- `fiona`
- `numpy`
- `pandas`

---

## **License**
This project is open for use and adaptation in accordance with the repository's license.

---
