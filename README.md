# Interactive_Map_Folium

# 🗺️ Folium + PyQt5 Interactive Map Viewer

A lightweight Python desktop application that embeds **interactive Leaflet maps** into a **native PyQt5 GUI** using `QWebEngineView`.

This serves as a foundation for future work in **urban visualization**, such as simulating **sunlight patterns** and **urban noise** throughout the day.

---

## 📌 Overview

This project demonstrates how to use **Folium** and **PyQt5** together to create a desktop map viewer. By leveraging `QWebEngineView`, the app renders a dynamic Folium map—pannable and zoomable—entirely within a native desktop interface.

It's a starting point for building:
- Standalone GIS tools
- Internal data dashboards
- Urban modeling apps
- Location intelligence platforms

---

## ✨ Features

- 🧭 Load and interact with a Leaflet map inside a PyQt5 window
- 🗺️ Default coordinates centered on New York City
- 🖼️ Full support for zooming, panning, and dynamic tile rendering
- 🔧 Clean, extensible codebase for adding new geospatial layers or simulation logic

---

## 🔧 Requirements

- Python 3.7 or higher
- Desktop environment (Windows, macOS, or Linux)

---

## 📦 Dependencies

Install required packages with:

```bash
pip install folium PyQt5 PyQtWebEngine
