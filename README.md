# WebGIS-Citywalk
A responsive web application designed for urban explorers to discover and plan walking tours in Guangzhou. This project integrates Mapbox GL and Amap (Gaode) API to provide high-performance 3D mapping, curated historical routes with storytelling, and a robust custom route editor featuring intelligent path smoothing algorithms.
## Key Features:

🗺️ Immersive 3D Mapping: Seamless integration of Mapbox GL and Amap API, supporting multiple base map styles (Standard, Satellite, Dark Mode) and 3D building visualization.

🎨 Interactive Route Editor: sophisticated custom route creation tool allowing users to add markers, drag-and-drop to reorder waypoints, and visualize paths instantly.

🧮 Advanced Algorithms:

Path Smoothing: Implemented Catmull-Rom Spline interpolation to generate smooth, natural-looking walking paths between custom waypoints.

Smart Clustering: Applied K-Means Clustering to optimize marker rendering and improve performance at different zoom levels.

Auto-Focus: Utilized Convex Hull algorithms to dynamically calculate map boundaries and fit routes within the viewport.

📱 Modern UI/UX: A responsive, glassmorphism-inspired interface built with Tailwind CSS, ensuring a smooth experience across both desktop and mobile devices.

💾 Local Persistence: Automatically saves custom routes and preferences using LocalStorage, allowing users to revisit their plans anytime.
