# Performance Viewer

A technical diagnostic tool for measuring and visualizing the runtime efficiency of JavaScript algorithms. This application provides real-time benchmarking for Big O complexity analysis.

## Business Value

Software performance directly impacts user retention and operational costs. Performance Viewer allows stakeholders to:
* Identify computational bottlenecks before they reach production.
* Compare different algorithmic approaches to ensure the most cost-effective solution is chosen.
* Visualize how systems scale as user data grows, preventing unexpected crashes or slowdowns.

## Technical Specifications

Performance Viewer is a high-fidelity diagnostic interface built with a focus on precision measurement:
* Benchmarking Engine: Utilizes the High Resolution Time API (performance.now) to capture microsecond-level execution data.
* Visualization Layer: Powered by Chart.js for rendering linear and non-linear complexity curves.
* Core Algorithms: Includes standard complexity profiles (O(1), O(n), O(n^2), O(log n)) for comparative analysis.
* Interactive Diagnostics: Allows technical users to plot custom data points and isolate specific function behaviors.

## Stack

* Frontend: HTML5, Tailwind CSS
* Visualization: Chart.js
* Engine: Vanilla JavaScript (ES6+)

## Setup

1. Clone the repository.
2. Open index.html in a browser to begin benchmarking.

Live Demo: https://ziadtaham.github.io/preformance-viewer/

---

Quality-focused performance diagnostics for reliable software systems.
