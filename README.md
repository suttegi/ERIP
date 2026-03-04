# ERIP

This project is dedicated to the collection and analysis of gameplay data from the game Risk of Rain 2.

## Project Structure

- **RoR2/**: Contains the C# source code for the BepInEx mod (`ScienceKit`) responsible for gathering in-game statistics.
- **Python/**: Includes a collection of Python scripts designed for processing, aggregating, and analyzing the data collected by the mod.
- **DATASET.csv**: The resulting dataset generated from the collected data.

## Overview

The `ScienceKit` mod captures detailed telemetry during gameplay sessions. The Python scripts are then used to transform and structure this raw data into a usable format for analysis, such as the included `DATASET.csv`. The analysis pipeline includes steps for data conversion, joining different data sources, and aggregating various in-game metrics.
