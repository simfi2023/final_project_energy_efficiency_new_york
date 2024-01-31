# Predicting Energy and Gas Savings

Welcome to this GitHub repository! Here, we embark on a journey to delve into the process of a machine learning project aimed at predicting residential gas and energy use. The data spans from 2007 to 2012, and captures insights from participants in the Home Performance with ENERGY STAR® program.

## Background
The Home Performance with ENERGY STAR® Program, a collaborative effort of the U.S. Environmental Protection Agency (EPA) and U.S. Department of Energy (DOE), stands as a beacon for promoting energy efficiency. The used data revolves around comparing estimated savings against normalized values derived from an open-source energy efficiency meter.

## About the Home Performance with ENERGY STAR® Program
"Home Performance with ENERGY STAR® is a national collaborative program between the U.S. Department of Energy and the U.S. Environmental Protection Agency. With 32 utility and nonprofit sponsors and 1,300 home performance contractors, it has been a trusted source since 2001. The program delivers home energy upgrades, enhancing safety, health, and energy efficiency. A rigorous quality assurance framework underscores its commitment." (source: [Department of Energy](https://www.energy.gov/eere/buildings/home-performance-energy-starr), retrieved 29.01.2024)

## Dataset Overview
The used dataset backcasts estimated modeled savings for a subset of completed projects in New York State, covering the period from 2007 to 2012. These projects are integral to the Home Performance with ENERGY STAR® Program, specifically under Residential Existing Homes (One to Four Units) Predicted First Year Savings for Energy Efficiency Measures: 2007 – 2012. This projects primary focus in this repository centers on cleaning and preparing the data for the development, training, and fitting of machine learning models aimed at precise predictions.

## Datasource
[Data - New York State](https://data.world/data-ny-gov/jtrr-tvq4) (Retrieved on 29.01.2024)

## Project Goal
The goal is to craft machine learning models with the prowess to predict residential gas and energy usage post-project completion, alongside estimating total project costs. This journey involves extracting valuable insights from the Home Performance with ENERGY STAR® dataset and employing cutting-edge algorithms for predictive analytics.


## Folder Structure:

### Data
- In the `data` folder, you'll discover both the raw and cleaned datasets for the Energy Efficiency project.

### Notebooks
- The `notebooks` folder encompasses four notebooks, each serving a unique purpose:
  1. **Cleaning Process Notebook:**
      - Detailed exploration and explanation of the data cleaning procedures.

  2. **Short Exploratory Data Analysis (EDA) Notebook:**
      - An overview of the data, highlighting key patterns and trends.

  3. **Machine Learning Models Code Notebook:**
      - Implementation of machine learning models for predicting energy efficiency.

  4. **Quick Statistical Testing Notebook:**
      - Swift statistical tests and analyses to complement the modeling process.

### Models
- The `models` folder houses the serialized models in pickle format for further use.



