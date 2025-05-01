# 📊 DataViz Project

An interactive data visualization project built with Python, Jupyter Notebook, and modern plotting libraries such as Seaborn, Plotly, Altair, and more.

---

## Features

- Clean and structured Jupyter Notebook workflow
- Interactive and static visualizations
- Widgets and dashboards using Voilà, ipywidgets, and Panel
- Optional geospatial support via Folium and GeoPandas

---

## ⚙️ Set Up

### 1. Clone the repository

```bash
git clone https://github.com/DedalusOsX/Dataviz---Group-project
cd Dataviz---Group-project
```
### 2. Set up env

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install project dependencies

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

### 3. Register the environment for Jupyter

```bash
python3 -m ipykernel install --user --name=dataviz-env --display-name "Python (dataviz-env)"
```

## 🚀 Run

```bash
jupyter notebook
```


## 🗃️ Project Structure


```bash
dataviz-project/
│
├── notebooks/               # Jupyter notebooks
│   └── main.ipynb           # Main visualization notebook
│
├── data/                    # Datasets
│   └── co2/                 
│   └── demography/          
│   └── education/    
│   └── electricity/   
│   └── gdp/    
│   └── inet/    
│   └── urbanization/    
├── README.md
├── 2020225_GroupProjectOnePager.pdf
├── requirements.txt
└── venv/                    # (Local virtual environment )
```