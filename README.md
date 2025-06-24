# Interactive_Map_Folium

# 🗺️ Folium + PyQt5 Interactive Map Viewer

A lightweight Python desktop application that embeds **interactive Leaflet maps** into a **native PyQt5 GUI** using `QWebEngineView`.

This serves as a foundation for future work in **urban visualization**, such as simulating **sunlight patterns** and **urban noise** throughout the day.

---

## 📌 Overview

This project demonstrates how to use **Folium** and **PyQt5** together to create a desktop map viewer. By leveraging `QWebEngineView`, the app renders a dynamic Folium map—pannable and zoomable—entirely within a native desktop interface.

It's a starting point for building:
- Standalone GIS tools
- Internal geospatial data dashboards
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
```

## 🧪 Testing

This app is currently tested manually through UI interaction.

Basic test checklist:

- ✅ Map loads correctly in PyQt5 window
- ✅ HTML is rendered by QWebEngineView
- ✅ App closes cleanly without errors
- ❌ No automated test suite yet

## ⚠️ Known Issues & Limitations

-Static map only (no time or real-time data support yet)
-No markers, overlays, or GeoJSON layers
-No export or save functionality
-Requires PyQtWebEngine, which may have OS-specific install issues


## Future Enhancements

This is an early prototype toward a geospatial simulation tool that visualizes:

-🕒 Shadow patterns over time using solar angles and building data
-🔊 Urban noise levels based on traffic data or synthetic estimation
-⏱️ Time-based sliders for simulating different hours of the day
-📍 Custom data overlays (e.g., population density, zoning)

```bash
coordinate = (37.7749, -122.4194)  # San Francisco

# Add a marker (extension idea)
folium.Marker(location=coordinate, popup="San Francisco").add_to(m)
```
