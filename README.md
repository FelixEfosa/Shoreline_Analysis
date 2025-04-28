# 🌊 Shoreline Analysis Web App
Visit here  https://shore-web-1-ucf1.onrender.com
![Description of Image](Images/111123.JPG)

## Description of the project.
This web app allows users to upload georeferenced satellite images, automatically detect and extract shorelines using deep learning models, visualize results on an interactive map, compare shoreline changes over time using transect analysis, and download outputs as shapefiles or GeoJSON files.

Built with Flask, Leaflet, LocalTileServer, and a custom shoreline detection model.

## ✨ Features

- Upload georeferenced images (GeoTIFF, etc.)
- Detect shorelines automatically with the AI model
- Visualize images and extracted shorelines on an interactive map (Leaflet)
- Download results as Shapefile / GeoJSON
- Compare two shoreline shapefiles using transects and compute distances
- Download comparison results
- Fully containerized (Docker support)
- Ready for Render deployment

## 🚀 Demo

![App Demo](assets/demo.gif)

[Live Demo](https://shore-web-1-ucf1.onrender.com) <!-- might remove later -->

## 🛠️ Installation

1. Clone the repository: git clone https://github.com/FelixEfosa/Shoreline_Analysis.git
2. Install dependencies: pip install -r requirements.txt
3. python app.py

## 📁 Project Structure

shoreline-analysis/ │ ├── app.py # Main Flask app ├── utils/ # Utility functions (image, geo processing) ├── templates/ # HTML templates ├── static/ # Static files (CSS, JS) ├── assets/ # Images for README ├── requirements.txt # Python dependencies ├── Procfile # For Gunicorn (Render deployment) ├── render.yaml # Render deployment config └── README.md # Project documentation

## 🛠️ Built With

- Python
- Flask
- Leafmap (Leaflet + Python)
- Geopandas
- Torch (PyTorch)
- Localtileserver
- Rasterio
- Shapely
- Gunicorn
- Docker (optional)

## 🤝 Contributing

Contributions are welcome!  
Please open an issue or submit a pull request for improvements, new features, or bug fixes.

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

## 🙏 Acknowledgements

- [Leafmap](https://leafmap.org/)
- [PyTorch](https://pytorch.org/)
- [LocalTileServer](https://github.com/banesullivan/localtileserver)

