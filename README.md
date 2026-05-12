# Node-RED Cold Wave Warning Dashboard

This project is a Node-RED based weather risk dashboard designed for elderly users.

## Overview
The system integrates data from the Taiwan Central Weather Administration Open Data API and processes temperature forecasts into an easy-to-read warning dashboard. It helps elderly users quickly understand cold weather risks and receive practical daily suggestions.

## Features
- Fetches weather forecast data from CWA Open Data API
- Groups 22 cities/counties into major regions
- Calculates cold-risk levels based on temperature thresholds
- Displays warning status with color indicators
- Provides dashboard-based visualization for easier access
- Includes a test region using Japan weather data

## Tech Stack
- Node-RED
- JavaScript
- REST API
- JSON
- Node-RED Dashboard
- HTML / CSS (Template Node)

## Project Structure
- `flows.json`: exported Node-RED workflow
- `report.pdf`: final project report
- `screenshots/`: project screenshots

## Risk Logic
- Red alert: temperature below 13°C
- Yellow alert: temperature between 13°C and 19°C
- Green safe: temperature above 19°C

## Data Source
- Taiwan Central Weather Administration Open Data API
- Open-Meteo API

## Notes
- API keys are removed for security
- This repository is for portfolio and demonstration purposes
