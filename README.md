# SAR-Based Multi-Hazard Early Warning System

## Phase 1: Flood Detection using Sentinel-1 SAR Data

This project aims to detect flooded and non-flooded areas using Sentinel-1 SAR backscatter data and machine learning.

## Problem Statement

Floods cause severe damage to lives, agriculture, infrastructure, and settlements. Traditional flood monitoring can be limited during cloudy weather or nighttime. SAR data is useful because it can capture Earth surface information in all weather and day/night conditions.

## Why Sentinel-1 SAR?

Sentinel-1 SAR data is useful for flood detection because water surfaces usually show low backscatter values. This makes it possible to identify flooded regions using machine learning and image analysis.

## Project Objective

Build a machine learning pipeline that can classify:

- Flooded areas
- Non-flooded areas

## Current Phase

Phase 1 focuses only on flood detection.

Future phases may include:

- Landslide susceptibility mapping
- Soil moisture risk analysis
- Combined multi-hazard risk index

## Tech Stack

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Rasterio
- GeoPandas
- Jupyter Notebook

## Project Structure

```text
SAR-MultiHazard-EarlyWarning-System/
│
├── data/
├── notebooks/
├── src/
├── reports/
├── images/
├── models/
├── README.md
├── requirements.txt
└── .gitignore

Sentinel-1 SAR Data
        ↓
Data Understanding
        ↓
EDA and Preprocessing
        ↓
Feature Extraction
        ↓
ML Model Training
        ↓
Flood / Non-Flood Classification
        ↓
Evaluation and Mapping