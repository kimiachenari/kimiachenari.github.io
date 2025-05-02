
<span style="font-size: 15px; color: #666666;">
    Welcome! I'm an urban planner focused on leveraging data-driven insights with expertise in **Street Network analysis**, **Big Data Analytics**, **Time Series Forecasting**, **Machine Learning**, and **Geospatial Analysis**.
</span>


---

## **Tools**
<span style="font-size: 15px; color: #666666;">- **Data Science Tools**: Python, R (4 years of experience), SQL (1 year of experience)  
<span style="font-size: 15px; color: #666666;">- **Geospatial Analysis - Open-Source Tools**: Google Earth Engine, Python, R (4 years of experience)  
<span style="font-size: 15px; color: #666666;">- **Geospatial Analysis Software**: QGIS, ArcGIS (6 years of experience)

---
<div style="text-align: center;">
    <img src="https://github.com/user-attachments/assets/60ab2699-28fe-4929-8964-6b86264e35c3" alt="vid">
</div>



## **Skills**
## **🌍 Spatial Analysis & Remote Sensing**
1. <span style="font-size: 20px; color: #333333;">**🗺️Street Network Analysis**  
<span style="font-size: 15px; color: #666666;">- Analyzed **street patterns** and assessed **street forms** that influence **surface temperature**.</span>  
<span style="font-size: 15px; color: #666666;">- Analyzed **connectivity** and **traffic volume**, identifying key areas.</span>  
<span style="font-size: 15px; color: #666666;">- Identified **urban functionality** through the relationship between streets and buildings.</span>  
<span style="font-size: 15px; color: #666666;">- Visualized **street orientation** and street geometry in ancient and hesitant areas.</span>  
<span style="font-size: 15px; color: #666666;">- Addressed pedestrian **accessibility** issues due to **inadequate** crossings.</span>

   
3. <span style="font-size: 20px; color: #333333;">**🌡️ Climate & Natural Hazard Analysis**  
   <span style="font-size: 15px; color: #666666;">- visualized **Land Surface Temperature (LST)** and improved the scaling of multiple observation maps.  
   <span style="font-size: 15px; color: #666666;">- visualized **air pollution** to identify environmental risks.  
   <span style="font-size: 15px; color: #666666;">- visualized **flood vulnerability** to evaluate risks and assist in disaster preparedness.

4. <span style="font-size: 20px; color: #333333;">**🏙️ Urban & GeoSpatial Data Science**  
<span style="font-size: 15px; color: #666666;">- Applied **NDVI**, **NDBI**, and **land cover classification** to assess **land use** and **environmental health**.</span>  
<span style="font-size: 15px; color: #666666;">- Predicted **land use patterns** using **deep learning** and **machine learning techniques**.</span>  
<span style="font-size: 15px; color: #666666;">- Developed **3D models** to visualize **building density** and infrastructure, providing insights into walkability and vehicular access.</span>  
<span style="font-size: 15px; color: #666666;">- Conducted a comprehensive **site selection analysis** for **residential construction**, considering critical factors such as elevation, slope, proximity to urban areas, roads, power network, and rivers; applied a weighted binary comparison matrix to identify and select the most suitable sites for development.</span>  
<span style="font-size: 15px; color: #666666;">- Visualized the **spread of COVID-19** in various regions of Iran over several weeks.</span>


5. <span style="font-size: 20px; color: #333333;">**🚗 Agent-Based Modeling**  
   <span style="font-size: 15px; color: #666666;">- Developed models for **traffic flow**.  
   <span style="font-size: 15px; color: #666666;">- Created **flood simulations** to assess evacuation strategies during floods.

## **📊 Data Science**

1. <span style="font-size: 20px; color: #333333;">**🤖 Machine Learning & Forecasting**  
   <span style="font-size: 15px; color: #666666;">- Built and applied **time series models** to improve **forecasting accuracy** with a global scale dataset.  
   <span style="font-size: 15px; color: #666666;">- Enhanced **regression** time series predictions using **Holt-Winters’ multiplicative smoothing**.  
   <span style="font-size: 15px; color: #666666;">- Improved **ARIMA** time series predictions by incorporating **external variables**.

2. <span style="font-size: 20px; color: #333333;">**💾 Big Data Management**  
   <span style="font-size: 15px; color: #666666;">- Managed and predicted outcomes using **real-world datasets** with numerous columns and limited rows.  
   <span style="font-size: 15px; color: #666666;">- Preprocessed, cleaned, and handled **large datasets**, ensuring data integrity for analysis.  
   <span style="font-size: 15px; color: #666666;">- Identified and analyzed **interconnections** across diverse data types.  
   <span style="font-size: 15px; color: #666666;">- Developed optimal strategies for forecasting **large datasets**, addressing real-world challenges like **missing data** and **inconsistencies**.

---

![عکس پروفایل3](https://github.com/user-attachments/assets/d0168479-ea7a-4381-a413-eb808a79e87e)

---

## 🔍 Current Interests

- AI for Disaster Preparedness & Resilient Infrastructure  
- Urban Heat Mitigation in Arid & Semi-Arid Regions  
- Geospatial Intelligence for Sustainable Development  
- Time Series Analysis of Environmental & Socioeconomic Indicators  

---

## 🤝 Let’s Collaborate

<span style="font-size: 15px; color: #666666;">I have had the opportunity to work with experts from Iran, Japan, Australia, Belgium, and New Zealand. I’m always open to research collaborations, innovative projects, or consulting opportunities. 

<div style="text-align: center;">
  <img src="https://github.com/user-attachments/assets/6e6440a0-72a6-4285-a5fb-139f925c2376" alt="collaboration" width="500"/>
</div>


---
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive World Map with Markers</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        #world-map {
            width: 100%;
            max-width: 900px;
            margin: 0 auto;
            display: block;
        }
        .country {
            fill: #ccc;
            stroke: #fff;
            cursor: pointer;
        }
        .country:hover {
            fill: #f90;
        }
        .marker {
            fill: red;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <h1>Click a Country</h1>
    <div>
        <svg id="world-map" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1000 500">
            <!-- Example country paths, replace with your actual paths -->
            <path class="country" id="country-australia" d="M300,300 L350,350 L300,400 L250,350 Z" data-name="Australia" />
            <path class="country" id="country-newzealand" d="M150,400 L200,450 L150,500 L100,450 Z" data-name="New Zealand" />
            <path class="country" id="country-japan" d="M500,150 L550,200 L500,250 L450,200 Z" data-name="Japan" />
            <path class="country" id="country-iran" d="M600,200 L650,250 L600,300 L550,250 Z" data-name="Iran" />
            <path class="country" id="country-belgium" d="M450,100 L500,150 L450,200 L400,150 Z" data-name="Belgium" />

            <!-- Markers for specific countries -->
            <!-- Australia Marker -->
            <circle class="marker" cx="325" cy="325" r="5" data-name="Australia" />
            <!-- New Zealand Marker -->
            <circle class="marker" cx="175" cy="450" r="5" data-name="New Zealand" />
            <!-- Japan Marker -->
            <circle class="marker" cx="525" cy="200" r="5" data-name="Japan" />
            <!-- Iran Marker -->
            <circle class="marker" cx="625" cy="250" r="5" data-name="Iran" />
            <!-- Belgium Marker -->
            <circle class="marker" cx="475" cy="150" r="5" data-name="Belgium" />
        </svg>
    </div>

    <div id="country-name">
        <p>Click on a country to see its name!</p>
    </div>

    <script>
        document.querySelectorAll('.country').forEach(country => {
            country.addEventListener('click', function() {
                let countryName = this.getAttribute('data-name');
                document.getElementById('country-name').innerHTML = `<p>You clicked: ${countryName}</p>`;
            });
        });

        // Add event listener for markers
        document.querySelectorAll('.marker').forEach(marker => {
            marker.addEventListener('click', function() {
                let markerName = this.getAttribute('data-name');
                document.getElementById('country-name').innerHTML = `<p>Marker for: ${markerName}</p>`;
            });
        });
    </script>
</body>
</html>



---
<span style="font-size: 15px; color: #666666;">📫 **Get in Touch**: [kimiachenary1@gmail.com]  
<span style="font-size: 15px; color: #666666;">🌐 **More**: [www.linkedin.com/in/kimiachenary]

---

<span style="font-size: 15px; color: #666666;">⭐ **Feel free to explore my repositories, and don’t forget to star what inspires you!**


