# Port Blair Vegetation Health Assessment 2023 🌿

## Introduction
Vegetation plays a critical role in maintaining ecological balance, supporting biodiversity, and regulating urban environments. Monitoring vegetation health is essential for sustainable land-use planning, urban expansion management, and ecosystem conservation.  

This project presents a **Vegetation Health Map of Port Blair (2023)** using NDVI (Normalized Difference Vegetation Index) derived from satellite imagery. The study highlights the spatial distribution of vegetation, identifies areas under stress, and provides insights for planners, environmentalists, and policymakers.

---

## Objective
The main objectives of this study are:  
1. Assess the current health and distribution of vegetation across Port Blair.  
2. Identify areas of dense, moderate, sparse, or stressed vegetation.  
3. Provide actionable insights for ecological monitoring, urban planning, and conservation initiatives.  

---

## Methodology / Workflow
The workflow of the study involves the following steps:

1. **Data Collection:**  
   - Satellite imagery covering Port Blair for 2023 was sourced from open-access platforms (e.g., Sentinel-2, Landsat).  

2. **Preprocessing:**  
   - Cloud masking and radiometric correction were applied.  
   - NDVI was calculated using the formula:  
     \[
     NDVI = \frac{(NIR - RED)}{(NIR + RED)}
     \]  

3. **Classification of Vegetation Health:**  
   NDVI values were classified into five categories:  
   - **Red:** Built-up / barren areas  
   - **Yellow:** Sparse vegetation  
   - **Light green:** Moderate vegetation  
   - **Green:** Healthy vegetation  
   - **Dark green:** Dense vegetation  

4. **Visualization:**  
   - The classified NDVI map was visualized using GIS tools to highlight spatial patterns and vegetation distribution.

---

## Results
- The **majority of Port Blair** is covered by moderate to dense, healthy vegetation (light green to dark green).  
- Very few red and yellow areas indicate **minimal urban or barren zones**.  
- The map effectively highlights areas under ecological stress and zones of thriving vegetation.  

*Example visualization:*  
![Port Blair Vegetation Health Map](images/PortBlair_VegetationHealthMap.png)

---

## Discussion
- The predominance of healthy vegetation demonstrates **strong forest cover and well-preserved natural landscapes** in Port Blair.  
- Few areas under stress suggest **low urban pressure** compared to other states or regions.  
- This analysis provides **data-driven insights** for conservation planning, urban development control, and sustainable ecosystem management.  
- Regular monitoring is recommended to track changes over time and ensure long-term ecological stability.  

---

## Conclusion
- Port Blair exhibits **predominantly healthy vegetation**, making it a model region for biodiversity and ecosystem conservation.  
- The NDVI-based vegetation health map serves as a **decision-support tool** for urban planners, environmentalists, and policymakers.  
- Future work can integrate temporal analysis to monitor vegetation trends and evaluate the impact of urbanization or climate factors on vegetation health.  

---

## Technologies & Tools Used
- **GIS Tools:** QGIS / ArcGIS for visualization and mapping  
- **Remote Sensing:** NDVI calculation using Sentinel-2 / Landsat imagery  
- **Data Processing:** Python (optional), Google Earth Engine (optional)  

---
