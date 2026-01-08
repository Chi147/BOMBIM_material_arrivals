
# BOMBIM_material_arrivals

```bash
git@github.com:Chi147/BOMBIM_material_arrivals.git
````

## Description

This module visualizes material arrivals on a construction site within a BIM model.
It uses an IFC 3D viewer (web-ifc) to display hot pink boxes that represent delivered materials.

## Features

* Load and view IFC models
* Render hot pink bounding boxes for material arrivals
* Real-time visual indication directly in the BIM scene

## Requirements

* Node.js
* npm

## Installation & Run

1. Install dependencies:

```bash
npm install
```

2. Navigate to the viewer directory:

```bash
cd engine_web-ifc/
```

3. Start the development server:

```bash
npm run dev
```

## Notes

* All logic is implemented on the frontend
* Material arrivals are represented visually only
* Ensure you are inside `engine_web-ifc` before running the dev server
