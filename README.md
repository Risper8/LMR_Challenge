# LMR Model Microsoft+Zindi Challenge 

## Overview
During disaster onset, microblogging posts containing critical information—such as requests for medical assistance, needs for food or shelter, reports of trapped individuals, and infrastructure damage—are only useful to response authorities if they include location details. While posts with precise GPS coordinates are rare, many do mention toponyms (e.g., names of places, areas, or streets), which authorities can use to approximate locations. However, the sheer volume of posts makes manual extraction of location cues unfeasible.

To address this, an automated system for recognizing and geolocating toponyms in microblogging posts is necessary.

The objective of this challenge is to encourage the development of automated Location Mention Recognition (LMR) systems for identifying location mentions in posts during emergencies. These systems aim to support relief activities led by response authorities during disasters.

This model is specifically designed to identify locations in tweets using token classification techniques

## Notebooks

- **location-mention-recognition(5)-Copy1-Copy.ipynb**: Contains code related to the LMR model.
- **trymodel1-Copy1.ipynb**: Contains code for model inference for predicting/Identifying the locations from the test data

## Data

The data used for the model is stored in JSON and CSV files.

## Tools and / Technologies Used

- Python
- Transformers
- spaCy

## Results
  
**WER score:** 0.167
