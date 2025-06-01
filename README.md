# 🛰️ Mangrove Vegetation Index (MVI) Mapper

**Mangrove Vegetation Index (MVI) Mapper (2019–Present)**  
Explore mangrove extent from 2019 onward across global mangrove forests using the Mangrove Vegetation Index (MVI), a robust spectral index for rapid and accurate mangrove classification.

---


## 🔗 Access the Tool via Google Earth Engine (Recommended) 
👉 (https://ee-abbaloloy.projects.earthengine.app/view/mvi)

---

## 🧪 About the Mangrove Vegetation Index (MVI)

The **Mangrove Vegetation Index (MVI)** utilizes three Sentinel-2 bands to identify mangrove areas based on greenness and moisture content.

**Formula:**

```
MVI = |NIR – Green| / |SWIR – Green|
```

**Where:**
- **NIR** = Near Infrared (Band 8)  
- **Green** = Visible Green (Band 3)  
- **SWIR** = Shortwave Infrared (Band 11)

---

## 🌿 How It Works

- `|NIR – Green|` captures greenness contrast between mangroves and terrestrial vegetation.  
- `|SWIR – Green|` expresses moisture content unique to mangroves — no tidal index needed.  
- Higher MVI → higher probability of pixel being classified as mangrove.

---

## 🌍 Applications

- Global mangrove extent mapping  
- Change detection from 2019 onward  
- Conservation and ecosystem monitoring  
- Coastal resource management

**Used by:**
- 🏛️ FAO (Food and Agriculture Organization)  
- 🌱 The Nature Conservancy  
- 🎓 Academic and research institutions

---

## 📚 Cite As

Baloloy, A.B., Blanco, A.C., Sta. Ana, R.R.C., Nadaoka, K. (2020).  
*Development and application of a new mangrove vegetation index (MVI) for rapid and accurate mangrove mapping.*  
**ISPRS Journal of Photogrammetry and Remote Sensing**, 166, 95–117.  
🔗 https://doi.org/10.1016/j.isprsjprs.2020.06.001

---

## 👨‍💻 Developer

**Alvin B. Baloloy**  
