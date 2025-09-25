# irp-wildfire-SCALED-viz
Visualizations from applying SCALED model to wildfire spread prediction

## Repository Structure

This repository contains visualizations organized by dataset and training phase:

- **01-data/**: Visualizations from Dataset 01

- **02-data/**: Visualizations from Dataset 02

- **03-data/**: Visualizations from Dataset 03

- **03-large-gif-viz/**: Large-scale rollout visualizations for specific wildfire cases over 12 hours
  - `gif-case-1.gif`: 12-hr rollout inference result in East Tehama, California, USA on 3.8km by 3.8km (40.322577,-121.915029)
  - `gif-case-13.gif`: 12-hr rollout inference result in Hollister, California, USA on 3.8km by 3.8km (36.812501,-121.26932)
  - `gif-case-15.gif`: 12-hr rollout inference result in San Benito, California, USA on 3.8km by 3.8km (36.558854,-121.109949)
  - `gif-case-16.gif`: 12-hr rollout inference result in Surprise Valley, California, USA on 3.8km by 3.8km (41.3436,-120.102824)
  - `gif-case-29.gif`: 12-hr rollout inference result in Newman, California, USA on 3.8km by 3.8km (37.759676,-120.714946)
  - `gif-case-36.gif`: 12-hr rollout inference result in Newman, California, USA on 3.8km by 3.8km (37.146164,-121.224374)
  - `gif-case-37.gif`: 12-hr rollout inference result in Sloughhouse, California, USA on 3.8km by 3.8km (38.569248,-121.15883)

## Folder Description

Each dataset folder contains three subfolders for different phases of the machine learning pipeline:
- **training**: Visualizations generated during model training
  - One timestep to the next
- **validation**: Visualizations from model validation
  - One timestep to the next
- **testing**: Final visualizations from model testing
  - Gifs spanning 6, 12 and 24 hrs
