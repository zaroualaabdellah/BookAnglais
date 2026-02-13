# Recipe Cookbook Application

A professional web application designed to create, manage, and export beautiful recipe pages in a fixed A4 format. This tool allows users to customize backgrounds, upload recipe images, and download their cookbook as PDF or PNG files.

## Features

- **A4 Fixed Layout**: Perfect for printing and creating physical cookbooks.
- **Dynamic Layout Adjustments**: Automatically resizes text and spacing for recipes with many ingredients.
- **Customizable Backgrounds**: Upload your own image or use the elegant default ornate background.
- **Editable Recipe Images**: Click on any recipe image to upload a new one from your library.
- **Batch Download**: Export the entire cookbook as a single PDF or individual PNG images.
- **Interactive Sidebar**: Manage settings, view recipe lists, and customize the book's appearance.

## Getting Started

1.  **Hosting**: This is a static web application. You can run it using any simple HTTP server.
    ```bash
    python3 -m http.server 8000
    ```
2.  **Access**: Open your browser and navigate to `http://localhost:8000`.
3.  **Usage**:
    - Use the sidebar to upload a custom background.
    - Click on a recipe image to replace it.
    - Use the navigation buttons to flip through pages.
    - Click "Download" to save your cookbook.

## Technical Details

- **Frontend**: HTML5, CSS3, Vanilla JavaScript.
- **Libraries**: 
  - `html2canvas` for capturing page elements.
  - `jsPDF` for generating PDF documents.
- **Design**: Responsive sidebar with a fixed-aspect-ratio A4 preview.

---
Developed by usf MSLh
# BookAnglais
