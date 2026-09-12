# egypt-eto-correction
Bias correction of ERA5-Land ETo over Egypt using CRNS and machine learning
# Bias Correction of ERA5-Land Reference Evapotranspiration over Egypt Using Cosmic-Ray Neutron Sensing and Machine Learning

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![Google Earth Engine](https://img.shields.io/badge/Google%20Earth%20Engine-4285F4?logo=google-earth&logoColor=white)](https://earthengine.google.com/)

## 📖 Overview

This repository contains the complete code, data processing scripts, and interactive tools developed for the study:

> **Khalifa, O.S., & Hegazi, A.M. (2026).** *Bias Correction of ERA5-Land Reference Evapotranspiration over Egypt Using Cosmic-Ray Neutron Sensing and Machine Learning.* [Journal Name], [Volume](Issue), [Pages]. DOI: [10.xxxx/xxxxx]

The study develops the first comprehensive framework for correcting systematic biases in ERA5-Land reference evapotranspiration (ETo) over Egypt, using Cosmic-Ray Neutron Sensor (CRNS) measurements from the Tamiya-Fayoum station as ground truth.

## 🎯 Key Findings

- **Systematic bias identified**: ERA5-Land overestimates ETo over Egyptian agricultural lands by **7.94%** (independently confirmed at **7.87%** using battery-derived radiation).
- **Seasonal pattern**: Bias ranges from **−13.7%** (winter) to **−4.9%** (summer).
- **Dominant drivers**: Vegetation cover (NDVI, partial r = −0.533) and wind speed (partial r = −0.142).
- **Correction model**: Random Forest reduced RMSE by **49%** (from 0.540 to 0.275 mm/day).
- **National product**: 12 monthly Correction Factor maps over Egypt at 500-m resolution.

## 🗂️ Repository Structure
