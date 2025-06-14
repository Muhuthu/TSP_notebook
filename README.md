## 🌍 Optimal Route Planning for Market Distribution

<div align="center">
  <img src="https://raw.githubusercontent.com/Muhuthu/TSP_notebook/main/Travelling-Salesman-Problem.jpg" alt="Optimal Route Visualization" width="700" style="max-width: 100%; height: auto;"/>
</div>

## 📋 Project Description

This repository contains a **Python solution** for optimizing product distribution routes across Kenya using advanced **Traveling Salesman Problem (TSP)** algorithms. The system provides a complete pipeline from location geocoding to interactive route visualization.

<div align="center">
  <img src="https://img.shields.io/badge/python-3.10%2B-blue?logo=python" alt="Python"/>
  <img src="https://img.shields.io/badge/jupyter-notebook-orange?logo=jupyter" alt="Jupyter"/>
  <img src="https://img.shields.io/badge/license-MIT-green" alt="License"/>
</div>

## ✨ Key Features

### 🗺 Geospatial Intelligence
- Automatic coordinate fetching using Nominatim API
- Location validation and error handling


### 📏 Distance Matrix
- Accurate geodesic distance calculations.
- Customizable distance metrics.

### ⚡ TSP Solvers
- Brute-force implementation (for small datasets)
- Heuristic approaches (for larger datasets)
- Performance benchmarking.

### 🎨 Visualization
- Interactive Folium maps
- Route animation capabilities
- Custom marker styling

## 🛠 Technology Stack

| Category        | Technologies                          |
|-----------------|---------------------------------------|
| **Core**        | Python 3.10+,jupyter                |
| **Data**        | NumPy, Pandas                         |
| **Visualization**| Matplotlib, Seaborn, Folium           |
| **Geospatial**  | Geopy, Nominatim                      |
| **Algorithms**  | Custom TSP implementations            |

## 💼 Use Cases

pie
    title Application Areas
    "Product Distribution" : 35
    "Delivery Services" : 30
    "Field Operations" : 20
    "Travel Planning" : 15

## 🚀 Getting Started

### Installation.
# Clone repository
git clone https://github.com/Muhuthu/TSP_notebook.git
cd route-optimizer

# Install dependencies
pip install -r requirements.txt.

# Launch Jupyter
jupyter notebook OptimalRoutePlanner.ipynb

## 📂 Repository Structure

TSP_notebook/
├── 📒 OptimalRoutePlanner.ipynb       # Main implementation
├── 📝 requirements.txt                # Dependencies
├── 📄 README.md                       # Documentation
├── 📁 data/                           # Sample datasets
└── 📁 images/                         # Visualizations
## 📍 Example Locations

<div align="center">

| Location | Coordinates |
|----------|-------------|
| Nairobi  | -1.2864, 36.8172 |
| Meru     | 0.0515, 37.6456 |
| Nyeri    | -0.4201, 36.9476 |
| Nandi    | 0.1833, 35.1333 |
| Kericho  | -0.3677, 35.2836 |
| Nakuru   | -0.3031, 36.0800 |

</div>

## 🤝 Contributing

We welcome contributions! Here's how to help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

**Focus Areas:**
- Enhancing algorithm efficiency and accuracy
- Improving data visualization clarity and interactivity
- Optimizing system performance and resource usage
- Updating and refining project documentation
- Strengthening code maintainability and readability
- Expanding test coverage for better reliability

## 📜 License

MIT License
Thanks to All Contributors.
