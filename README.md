# 🌞 Global Solar Power Plants Dataset  
### An Institutional Research Initiative on Solar Energy, Geospatial Data and Machine Learning
---
<div align="left">

### 👥 Principal Collaborators

<table>
<tr>
<td align="center" width="130">
<img src="extra/images/anibal.jpg" width="70"/><br/>
<sub><b>Anibal Mantilla-Guerra</b></sub><br/>
<sub>Central University of Ecuador</sub><br/>
<a href="https://orcid.org/0000-0000-0000-0001">ORCID</a>
</td>
<td align="center" width="130">
<img src="extra/images/christian.jpg" width="70"/><br/>
<sub><b>Christian Mejia-Escobar</b></sub><br/>
<sub>Central University of Ecuador</sub><br/>
<a href="https://orcid.org/0000-0000-0000-0002">ORCID</a> ·
</td>
<td align="center" width="130">
<img src="extra/images/jose.jpg" width="70"/><br/>
<sub><b>Jose Garcia-Rodriguez</b></sub><br/>
<sub>University of Alicante</sub><br/>
<a href="https://orcid.org/0000-0000-0000-0003">ORCID</a>
</td>
<td align="center" width="130">
<img src="extra/images/jorge.jpg" width="70"/><br/>
<sub><b>Jorge Azorin-Lopez</b></sub><br/>
<sub>University of Alicante</sub><br/>
<a href="https://orcid.org/0000-0000-0000-0003">ORCID</a>
</td>
<td align="center" width="130">
<img src="extra/images/fernando.jpg" width="70"/><br/>
<sub><b>Byron Fernando Tarco</b></sub><br/>
<sub>Central University of Ecuador</sub><br/>
<a href="https://orcid.org/0000-0000-0000-0005">ORCID</a>
</td>
<td align="center" width="130">
<img src="extra/images/karen.jpg" width="70"/><br/>
<sub><b>Karen Santamaria Hernandez</b></sub><br/>
<sub>Central University of Ecuador</sub><br/>
<a href="https://orcid.org/0000-0000-0000-0005">ORCID</a>
</td>
</tr>
</table>

---

### 🛠️ Support Team

<table>
<tr>
<td align="center" width="130">
<img src="extra/images/martin.jpg" width="50"/><br/>
<sub><b>Martin Sarmiento</b></sub><br/>
</td>
<td align="center" width="120">
<img src="extra/images/luis.png" width="50"/><br/>
<sub><b>Fernando Neira</b></sub><br/>
</td>
<td align="center" width="120">
<img src="extra/images/carlos.jpg" width="50"/><br/>
<sub><b>Carlos Ramirez</b></sub><br/>
</td>
<td align="center" width="120">
<img src="extra/images/yuleidi.jpg" width="50"/><br/>
<sub><b>Juleydi Miles</b></sub><br/>
</td>
<td align="center" width="120">
<img src="extra/images/shelby.jpg" width="50"/><br/>
<sub><b>Shelby Gualan</b></sub><br/>
</td>
</tr>
</table>

---

## 📍 Project Context

This repository hosts the official products of a **research project developed within an academic and institutional framework**, focused on the **systematic compilation, analysis, and modeling of global solar power plant data**.

The project is conducted by a **university research group / laboratory**, with the objective of supporting:

- scientific research on renewable energy
- data-driven spatial planning
- machine learning–based decision support
- open and reproducible science

---

## 🎯 Objectives

The main objectives of this project are:

1. To construct a **global, structured, and high-quality dataset** of solar power plants.
2. To generate **derived geospatial products** (raster and vector) for spatial analysis.
3. To develop a **machine learning model** for predicting optimal locations for solar plant deployment.
4. To provide an **interactive web platform** for statistical exploration and dissemination of results.

---

## 📊 Core Dataset

The primary product is a **tabular dataset** containing:

- 🌍 **Worldwide coverage**
- 🏭 **Approximately 50,000 solar power plant records**
- 🧾 **26 attributes per record**

### Attribute groups include:
- Geographic and spatial variables
- Technical characteristics of solar installations
- Environmental and climatic indicators
- Infrastructure and accessibility variables
- Socioeconomic and territorial context

📁 **Format:** CSV (tabular)  
📌 **Designed for:** data analysis, GIS integration, and machine learning pipelines

### 📊 Dataset Sample (Extract)

| IDENTIFICACIÓN |                                 | UBICACIÓN |                          |            |            | TERRENO   |             |         |   |            |                    |           |                                  |            |           |                    | CLIMA       |                    |                |                      |                      |           |               |            | TÉCNICO   |                    |                        |
|----------------|---------------------------------|-----------|--------------------------|------------|------------|-----------|-------------|---------|---|------------|--------------------|-----------|----------------------------------|------------|-----------|--------------------|-------------|--------------------|----------------|----------------------|----------------------|-----------|---------------|------------|-----------|--------------------|------------------------|
| CÓDIGO         | NOMBRE                          | PAÍS      | ESTADO                   | LONGITUD   | LATITUD    | ELEVACIÓN | ÁREA        | TAMAÑO  |   | PENDIENTE  | T_PENDIENTE        | CURVATURA | T_CURVATURA                      | ASPECTO    | T_ASPECTO | DISTANCIA A LA VIA | TEMPERATURA | IRRADIANCIA GLOBAL | HUMEDAD        | VELOCIDAD DEL VIENTO | DIRECCIÓN DEL VIENTO | DT_VIENTO | APTITUD SOLAR | T_APTITUDS | CAPACIDAD | INCLINACIÓN ÓPTIMA | POTENCIAL FOTOVOLTÁICO |
|                |                                 |           |                          | Grados (°) | Grados (°) | msnm      | m^2         |         |   | Grados (°) |                    |           |                                  | Grados (°) |           | m                  | °C          | kWh/m^2            | Porcentaje (%) | m/s                  | Grados (°)           |           |               |            | MW        | Grados (°)         | kWh/kWp                |
| 00127-ARG-P    | Aconcagua solar farm            | Argentina | announced                | -68.8713   | -32.998501 | 929       | 250.337006  | Pequeña | P | 0.574179   | Plano o casi plano | 0.000795  | Superficies planas o intermedias | 55.124672  | Northeast | 127.282704514241   | 12.6        | 6.11               | 53.74          | 3.7789               | 55.099998            | Northeast | 0.746197      | Alta       | 25        | 31                 | 4.983                  |
| 00129-ARG-G    | Altiplano 200 Solar Power Plant | Argentina | operating                | -66.895798 | -24.1392   | 4000      | 4397290     | Grande  | G | 1.60257    | Plano o casi plano | -0.002781 | Superficies planas o intermedias | 188.707367 | South     | 56014.9540283688   | 6.8         | 8.012              | 53.74          | 7.02062              | 55.099998            | Northeast | 0.8           | Alta       | 101       | 26                 | 6.389                  |
| 00130-ARG-P    | Altiplano 200 Solar Power Plant | Argentina | operating                | -66.926102 | -24.073999 | 4000      | 5774.399902 | Pequeña | P | 6.24265    | Moderado           | -0.043699 | Superficies cóncavas / Valles    | 270.913513 | West      | 52696.7857245898   | 6.8         | 7.878              | 53.74          | 8.32836              | 55.099998            | Northeast | 0.726996      | Alta       | 107       | 26                 | 6.392                  |
| 00131-ARG-P    | Anchoris solar farm             | Argentina | construction             | -68.915001 | -33.330101 | 937       | 645.163025  | Pequeña | P | 0.902748   | Plano o casi plano | 0.002781  | Superficies planas o intermedias | 108.434952 | East      | 335.928003133715   | 13.1        | 6.119              | 53.74          | 3.87037              | 55.099998            | Northeast | 0.595309      | Media      | 180       | 31                 | 4.969                  |
| 00132-ARG-P    | Antu Newen solar farm           | Argentina | cancelled - inferred 4 y | -70.269897 | -37.375801 | 865       | 241.276001  | Pequeña | P | 1.79147    | Plano o casi plano | -0.002384 | Superficies planas o intermedias | 239.349335 | Southwest | 34.0097334164884   | 11.4        | 6.223              | 53.74          | 6.55962              | 55.099998            | Northeast | 0.657269      | Alta       | 20        | 33                 | 5.002                  |
| 00133-ARG-P    | Arauco Hybrid solar farm        | Argentina | pre-construction         | -66.817299 | -28.554899 | 858       | 30          | Pequeña | P | 1.87201    | Plano o casi plano | -0.009137 | Superficies planas o intermedias | 56.188801  | Northeast | 314.15128971256    | 18.799999   | 6.741              | 51.49          | 7.18792              | 114.8                | Southeast | 0.743481      | Alta       | 50.400002 | 30                 | 5.368                  |
| 00137-ARG-P    | Armonia solar farm              | Argentina | operating                | -67.957199 | -33.431499 | 570       | 2201.669922 | Pequeña | P | 0.191517   | Plano o casi plano | 0.002781  | Superficies planas o intermedias | 63.434948  | Northeast | 9404.1513460746    | 17.700001   | 6.094              | 53.74          | 5.36097              | 55.099998            | Northeast | 0.748652      | Alta       | 28        | 31                 | 4.876                  |
| 00138-ARG-G    | Cafayate Solar Plant            | Argentina | operating                | -65.923203 | -26.032301 | 1612      | 2544020     | Grande  | G | 1.10853    | Plano o casi plano | 0.000397  | Superficies planas o intermedias | 101.888657 | East      | 2887.13397002308   | 16          | 7.014              | 53.74          | 7.16562              | 55.099998            | Northeast | 0.8           | Alta       | 100       | 29                 | 5.547                  |
| 00139-ARG-G    | Caldenes Del Oeste solar farm   | Argentina | operating                | -66.388    | -33.297199 | 665       | 1004700     | Grande  | G | 0.528349   | Plano o casi plano | 0         | Superficies planas o intermedias | 271.548157 | West      | 585.192917590384   | 18.4        | 5.99               | 53.74          | 8.102                | 55.099998            | Northeast | 0.670959      | Alta       | 30        | 31                 | 4.78                   |
| 00140-ARG-G    | Cauchari Solar Power Complex    | Argentina | operating                | -66.723701 | -24.094999 | 3989      | 10738800    | Grande  | G | 0.641232   | Plano o casi plano | -0.002384 | Superficies planas o intermedias | 286.821411 | West      | 41632.5789384461   | 6.6         | 8.031              | 53.74          | 5.4822               | 55.099998            | Northeast | 0.8           | Alta       | 105       | 27                 | 6.392                  |
| 00141-ARG-P    | Cauchari Solar Power Complex    | Argentina | operating                | -66.7248   | -24.091499 | 3989      | 30          | Pequeña | P | 0.451402   | Plano o casi plano | -0.001589 | Superficies planas o intermedias | 304.69516  | Northwest | 41891.6610878239   | 6.6         | 8.029              | 58.23          | 5.47306              | 82.1                 | East      | 0.8           | Alta       | 105       | 27                 | 6.394                  |


<img width="5570" height="238" alt="image" src="https://github.com/user-attachments/assets/06c1330b-c45d-482c-b6da-4bbc85ebf56c" />


---

## 🗺️ Geospatial Data Products

As part of the research workflow, additional **geospatial datasets** were produced.

### Vector data
- Solar power plant locations
- Supporting spatial layers

### Raster data
- Environmental suitability layers
- Climatic and geographic indicators
- Derived spatial variables

📁 **Formats:** GeoTIFF, Shapefile, GeoPackage  
📐 **Compatible with:** QGIS, ArcGIS, GRASS GIS, and spatial ML frameworks

---

## 🧠 Machine Learning Model

The repository includes a **Jupyter Notebook** implementing a **neural network–based machine learning model** aimed at:

> **Predicting optimal sites for solar power plant installation**

### Model characteristics:
- Multivariate input derived from the 26 dataset attributes
- Neural network architecture implemented using Keras / TensorFlow
- Data preprocessing, normalization, and feature engineering
- Model training, validation, and performance evaluation
- Spatial interpretation of predicted suitability

📓 The notebook is fully documented to ensure **reproducibility and transparency**.

---

## 🌐 Web-Based Statistical Analysis Platform

To facilitate access and dissemination, a **web-based platform** was developed as part of the project.

<a href="https://mssarmientoo.github.io/figempa/" target="_new"><img src="extra/images/website.png" width="800"/></a>

### Platform capabilities:
- Descriptive and exploratory statistical analysis
- Interactive data visualizations
- Summary indicators and distributions
- User-friendly interface for non-technical users

This platform is intended for **researchers, students, and policy analysts**, enabling data exploration without requiring programming expertise.

---

## 📂 Repository Structure


---

## 🎓 Intended Use

This repository is intended to support:

- Academic research and publications
- Graduate and undergraduate teaching
- Methodological development in geospatial AI
- Energy planning and policy-oriented studies
- Open data and reproducible science initiatives

---

## 📜 License and Use

This project is released under the  
**Creative Commons Attribution–NonCommercial 4.0 International (CC BY-NC 4.0)** license.

- Attribution to the authors and institution is required.
- Commercial use is not permitted without prior authorization.

---

## 🏛️ Institutional Affiliation

**Research Group / Laboratory:**  
*Department of Computer Technology*  

**Institution:**  
*University of Alicante*  

**Country:**  
*Spain*

---

## 🤝 Collaboration and Contributions

The project is open to **academic collaboration**.

Contributions may include:
- Data validation and enrichment
- Additional geospatial layers
- Model extensions and benchmarking
- Documentation and methodological improvements

Please use GitHub **Issues** or **Pull Requests** to contribute.

---

## 📬 Contact

For academic collaboration, data usage inquiries, or citation information:

📧 *armantilla@uce.edu.ec*  
🌐 *www.uce.edu.ec*

---

> *This project contributes to the advancement of renewable energy research through open data, geospatial analysis, and machine learning within an institutional academic framework.*
