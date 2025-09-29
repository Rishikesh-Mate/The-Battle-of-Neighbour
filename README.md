# 🏪 Vancouver Safe Location Analysis – Business Problem  

A data science project aimed at identifying the safest boroughs and neighborhoods in Vancouver, Canada, to open a new commercial establishment (e.g., a grocery store). This project combines crime data analysis, venue exploration, and machine learning clustering to support data-driven decision-making.  

---

## 📊 Project Overview  
The goal is to recommend a safe, business-viable location by:  
- Identifying the **safest borough** in Vancouver using crime data (2003–2019).  
- Exploring **neighborhood venues** to find areas with lower grocery store density.  
- **Clustering neighborhoods** based on venue similarity to recommend optimal business locations.  

---

## 🛠️ Tools & Technologies  
- **Programming & Libraries:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **APIs:** Foursquare API (venue data), OpenCage Geocoder (geolocation)  
- **Machine Learning:** K-Means Clustering (unsupervised learning)  
- **Visualization:** Folium (interactive maps), Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook  

---

## 📂 Dataset  
- **Part 1:** [Kaggle – Vancouver Crime Data (2003–2019)](https://www.kaggle.com/agilesifaka/vancouver-crime-report/version/2)  
- **Part 2:** Borough and neighborhood information from Wikipedia  
- **Part 3:** Venue data via Foursquare API  

Features include:  
TYPE (Crime Type), YEAR, MONTH, DAY, HOUR, NEIGHBOURHOOD, GPS coordinates, etc.  

---

## 🔑 Key Steps  
1. **Crime Data Analysis**  
   - Cleaned and normalized Vancouver crime dataset.  
   - Visualized borough-wise crime density to identify the safest borough.  

2. **Neighborhood & Venue Exploration**  
   - Mapped neighborhoods using OpenCage Geocoder + Folium.  
   - Collected top 10 venues per neighborhood using Foursquare API.  

3. **Clustering & Recommendations**  
   - Applied **K-Means Clustering** to group neighborhoods based on venue types.  
   - Shortlisted neighborhoods where grocery stores were underrepresented.  

4. **Visualization**  
   - Created Folium maps to display clusters and safe neighborhoods interactively.  

---

## 📈 Results  
- Identified **safest boroughs** and shortlisted neighborhoods with low grocery store density.  
- Recommended optimal neighborhoods for opening a grocery store based on data-driven clustering.  

---

## 🚀 Future Work  
- Automate real-time crime data ingestion for dynamic recommendations.  
- Integrate population and demographic data for better business decision-making.  

---

## 📬 Contact  
**Author:** Rishikesh Mate  
📧 Email: [rishikeshmateofficial@gmail.com](mailto:rishikeshmateofficial@gmail.com)  
🔗 [LinkedIn](https://linkedin.com)  
