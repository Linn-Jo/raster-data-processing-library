# Raster Data Processing & Benchmarking Library

## Overview
This project implements a multi-environment **Raster Data Processing Library** designed to load, process, and visualize geospatial raster datasets. The primary objective is to evaluate and benchmark execution performance and memory efficiency across multiple runtime environments:
- **Native Python**
- **JavaScript (In-browser execution)**
- **PyScript & Pyodide (WebAssembly-based client-side Python)**

## Key Features
- **Data Loading:** Efficient parsing of large, multi-dimensional array structures using Zarr and Xarray formats.
- **Aggregation Operations:** Computes statistical metrics (mean, median, min, max, variance, sum) on raster datasets.
- **Browser Visualization:** Directly renders processed geospatial metrics within interactive web environments.
- **Performance Benchmarking:** Comparative execution speed and memory overhead analysis across JS, Wasm, and Python engines.

## Tech Stack
- **Languages:** Python, JavaScript, HTML/CSS
- **WebAssembly Runtimes:** PyScript, Pyodide
- **Data & Math Libraries:** Zarr, Xarray, Matplotlib, NumPy

## Project Structure
- `JS/` - JavaScript implementation for browser-native benchmarking.
- `Pyodide/` - WebAssembly-based processing engine (`raster_library` core functions).
- `Pyscript/` - PyScript integration for client-side Python execution.
- `Python/` - Native Python execution code for baseline speed comparison.
