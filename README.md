# ML-Climate-Classification

## Project Overview

This project serves the mission of ClimateWins, a fictional climate advocacy nonprofit dedicated to understanding and communicating climate change impacts across Europe through data-driven analysis and accessible machine learning applications. Our focus is on developing robust machine learning models to classify weather conditions as "pleasant" or "unpleasant" across 15 locations throughout Europe, spanning over six decades of meteorological data (1960-2022).

By leveraging historical weather patterns, we aim to:

- Quantify climate comfort trends across different European regions over time
- Identify regional variations in weather pleasantness and their evolution
- Provide evidence-based insights for climate advocacy and policy discussions
- Demonstrate accessible AI applications for environmental research and public education

## Data Overview

This analysis uses a subset of the European Climate Assessment and Dataset containing:

- 344,250 daily observations across 15 European weather stations
- 62+ years of historical data (January 1960 to October 2022)
- 9 meteorological variables including temperature, humidity, precipitation, wind speed, and hours of sunshine
- Binary classification targets indicating pleasant vs. unpleasant weather conditions for each date and location

## Methodology

This project employs multiple supervised machine learning algorithms to tackle the weather classification challenge:

- k-Nearest Neighbors (k-NN): Baseline proximity-based classification
- Decision Trees: Interpretable rule-based weather pattern identification
- Multi-Layer Perceptrons (MLPs): Artificial neural network that employs deep learning for complex pattern recognition
