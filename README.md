# Capstone Project – The Battle of Neighborhoods  
**Author**: Peter Haro  
**Email**: pharo8496@gmail.com
**More**: Software 7 AI Engineer @ HaroNext Innovations 
**Reach** https://haronext.com
**Date**: August 2025  
    
---

This notebook includes web scraping, data cleaning, and mapping using `folium` and clustering using `k-means`.
Thanks to all data sources.

## 📌 Project Objective  
Analyze neighborhoods in Scarborough, Toronto to identify optimal areas to live using location clustering.
The goal is to help people find better places to live based on geographical and service-based data.

## 🛠️ Technologies Used  
- Python  
- Jupyter Notebook  
- Folium  
- BeautifulSoup  
- Geocoder  
- Scikit-learn (KMeans Clustering)

## 📂 Files Included  
- `Battle-of-Neighbourhoods.ipynb` – The full Jupyter Notebook with code and outputs  
- `requirements.txt` – Python dependencies to install  
- `LICENSE` – Project license (MIT)  
- `README.md` – This file  


## 🖥️ OPTION 1: Run Locally via Jupyter Notebook

### Step 1: Install Python (if you don’t have it)  
Download and install from [python.org](https://www.python.org/downloads/).

### Step 2: Install Jupyter Notebook  
Open your terminal (Command Prompt, PowerShell, or Bash) and run:

```bash
pip install notebook
```
Step 3: Install Project Dependencies
Install all required Python packages using:
```bash
pip install -r requirements.txt
```

Step 4: Run Jupyter Notebook
Navigate to the project folder containing Battle-of-Neighbourhoods.ipynb:
cd path/to/your/project-folder

Then launch Jupyter Notebook:
```bash
jupyter notebook
```
A browser window will open automatically. Click on Battle-of-Neighbourhoods.ipynb to open the notebook.


## Troubleshooting
If running jupyter notebook shows 'jupyter' is not recognized, try:
```bash
python -m notebook
```


🖥️ OPTION 2: Export Results-Only HTML (Hide Code)

You can export your notebook as an HTML file that hides all the code cells but keeps markdown, charts, maps, and outputs.

Run this command from your terminal in the project directory:
```bash
jupyter nbconvert --to html --TemplateExporter.exclude_input=True "Battle-of-Neighbourhoods.ipynb"
```

This creates Battle-of-Neighbourhoods.html that you can share or present easily.


## 📍 Output  
Interactive maps, cluster visualizations, and insights for urban planning.

## 🔗 Contact  
For any questions or collaborations, contact **Peter Haro** via [LinkedIn](https://www.linkedin.com/in/peter-haro-23a627230/) or [Email](mailto:pharo8496@gmail.com) or [Company](www.haronext.com)
