# ⊹ Traverse Plotter

### Survey Data Visualization Tool for DENR Cartographers & GIS Personnel

---

## 📌 Overview

**Traverse Plotter** is a web-based application designed to convert raw bearing-and-distance traverse data into accurate, customizable cartographic outputs.

Built by Jay Lord P. Diniega for **DENR cartographers, GIS analysts, land surveyors, and mapping professionals**, the tool streamlines the workflow from field survey data to clean boundary plots ready for documentation and reporting.

The application runs entirely in the browser — no installation required.

---

## 🎯 Purpose

Traverse Plotter supports:

- Cadastral boundary plotting
- Land classification mapping
- Technical description visualization
- Boundary verification and checking
- GIS workflow preparation
- Survey data validation before submission

---

## ✨ Features

### 📋 1. Data Input & Parsing

- Paste standard survey format:

  ```
  FROM-TO  N/S  DEG  MIN  [SEC]  E/W  DIST
  ```

- Automatic traverse sorting
- Editable data table
- Add, delete, reorder lines
- Undo/redo functionality
- Save and load project files (.json)

---

### 📐 2. Live Traverse Plot

- Automatic coordinate computation
- Real-time boundary plotting
- Pan and zoom controls
- Point labeling
- Dot and line visualization

---

### ✏️ 3. Export & Editing Mode

#### Traverse Styling

- Adjustable line color and thickness
- Dot size control
- Label toggle and font customization
- Automatic inside-label placement

#### Drawing & Annotation Tools

- Text tool (custom fonts, bold option)
- Straight line tool
- Polyline tool
- Snap-to-traverse points
- Arrowheads and dash styles
- Select, move, rotate, delete objects
- Canvas undo/redo system

---

### 🖼 4. Output & Export

- Custom canvas size (width & height)
- Adjustable padding
- Fit-to-view option
- Full-screen preview
- Export as:
  - PNG download
  - Transparent PNG (copy to clipboard)

---

## 🗂 Workflow

1. Paste or load survey data
2. Parse and verify live plot
3. Switch to Export & Edit mode
4. Customize styling and annotations
5. Export final boundary map

---

## 🧮 Technical Capabilities

- Bearing-to-azimuth conversion
- Coordinate computation using trigonometric functions
- Dynamic scaling and centering
- Snap-based precision drawing
- Canvas-based rendering (HTML5)
- Fully client-side processing

---

## 👥 Intended Users

- DENR Cartographers
- GIS Analysts
- Land Surveyors
- Civil Engineering Professionals
- Academic institutions teaching surveying

---

## 💻 Technology Stack

- HTML5
- CSS3
- JavaScript (Vanilla)
- Canvas API

No external backend required.

---

## 📁 File Structure

```
appv2.html
```

The entire application is contained within a single HTML file for portability and easy deployment.

---

## 🚀 Deployment

Because the app is fully client-side, it can be:

- Opened directly in a browser
- Hosted via GitHub Pages
- Deployed on any static hosting platform

---

## 📜 License

For institutional or DENR internal use.
Modify and adapt as required for official workflows.

---
