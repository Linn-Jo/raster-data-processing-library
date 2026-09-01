# Raster Data Processing Library

## Project Overview

This project demonstrates the implementation of a Raster Data Processing Library using multiple environments, including JavaScript, Python, and PyScript. The library is designed to load, process, and visualize geospatial raster data, providing essential aggregation operations like mean, median, minimum, maximum, and more.

The goal of this project is to compare the performance of raster data processing across different environments, such as native Python, PyScript (browser-based Python using WebAssembly), and JavaScript. 

## Key Features

- Efficient raster data loading from Zarr format.
- Perform aggregation operations (mean, median, min, max, variance, sum, etc.).
- Visualize raster data directly within a web browser.
- Performance benchmarking for execution time and memory usage across different environments.
- Interactive user interface for selecting and processing raster data.

## Technologies Used

- **JavaScript**: Used for loading raster data and performing operations directly in the browser.
- **Python**: Used for native raster data processing and visualization.
- **PyScript**: WebAssembly-based Python implementation that enables running Python code in the browser.
- **Zarr**: Data format for large, multi-dimensional arrays.
- **Xarray**: Python library for handling multi-dimensional datasets.
- **Matplotlib**: Visualization library for generating plots.
- **WebAssembly (Wasm)**: Technology that allows running compiled Python code efficiently in a browser.

## Project Structure

- **JS**          # JavaScript code for loading for benchmarking purposes
- **Pyodide**        # Pyodide code processing raster data - **raster_library** contains the core functions for raster data processing (e.g., mean, median, min, max, variance, sum, etc.).
- **Pyscript**        # Pyodide copy in Pyscript for benchmarking purposes
- **Python**         # Python code for native execution speed comparison
- **README.md**           # Project documentation
