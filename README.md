# Group-4-Final-Product

## Project Overview

This repository contains resources for a web-based project related to biomarkers and inflammatory pathways. The primary focus is on visualizing key signaling pathways involved in inflammation, such as CRP (C-reactive protein), IL-1, IL-6, and TNF. These visualizations help in understanding the role of these biomarkers in various physiological and disease processes.

The project is built with a simple HTML, CSS, and image-based structure. It includes an informative website that presents these pathways alongside their respective images. The website is styled with custom CSS to ensure an engaging and clean user experience.

This project was developed during the **Practical Programming in the Life Sciences (2425-PRA3006)** course at **Maastricht University**, in the **Maastricht Science Programme** bachelor's degree. 

The objective of the course is to learn how to interact with SPARQL endpoints using JavaScript and visualize the results graphically with libraries like **d3.js** or **Cytoscape.js**.

## Features:
- **Biomarker Pathways**: Visual representations of inflammatory pathways like CRP, IL-1, IL-6, and TNF.
- **Responsive Website**: Basic HTML and CSS layout for presenting the pathways and relevant content.
- **Images**: High-quality pathway diagrams to visualize the biological processes.

## Project Structure:
- **Images**: Contains images for various inflammatory pathways (e.g., CRP, IL1, IL6, TNF).
- **Website**: Contains HTML and CSS files for the website layout and design.

## Getting Started

To get a local copy of this project up and running, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Group-4-Final-Product.git
   ```

2. **Navigate to the website directory**:
   ```bash
   cd Group-4-Final-Product/website
   ```

3. **Set up d3.js**: 
The project uses the d3.js library for data visualization. You can include it in two ways:

Option 1: Use a CDN (recommended): Ensure the following <script> tag is included in the <head> section of your HTML file:
<script src="https://d3js.org/d3.v6.min.js"></script>

Option 2: Download d3.js locally:

Download the library from d3js.org.
Save it in a js directory within your project structure (e.g., Group-4-Final-Product/website/js/).
Include it in your HTML file:
<script src="js/d3.v6.min.js"></script>
   
4. **Open the `homepage.html` file in your preferred web browser to view the project.**

*Contributions are welcome! If you'd like to improve the website or add new pathway visualizations, feel free to fork the repository and submit a pull request.*
