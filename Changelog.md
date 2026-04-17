CHANGELOG.md
All notable changes to this project will be documented in this file.
The format is based on Keep a Changelog, and this project adheres to Semantic Versioning.

[1.0.0] - 2026-04-17
Added
Data Collection: Implemented BeautifulSoup script to scrape Falcon 9 launch records from Wikipedia.

API Integration: Added SpaceX REST API functions to pull technical details (booster, payload, core data).

EDA SQL: Created a complete SQL analysis suite for mission success querying.

Folium Analytics: Integrated interactive map with marker clusters and proximity lines for launch site analysis.

ML Modeling: Added Logistic Regression, SVM, Decision Tree, and KNN models with GridSearchCV optimization.

Changed
Wrangling Pipeline: Updated data cleaning steps to handle nulls in PayloadMass using mean imputation.

Feature Engineering: Converted categorical data to numeric using One-Hot Encoding for the machine learning matrix.

Visuals: Refined Seaborn plots for better readability in the final presentation.

Fixed
Coordinate Accuracy: Corrected launch site GPS coordinates for more precise Folium distance calculations.

Class Mapping: Fixed binary label logic for "Ocean" and "ASDS" landing outcomes.

How to maintain it:
Reverse Chronological: Always put the newest version at the top.

Categories: Use these standard headers:

Added for new features.

Changed for changes in existing functionality.

Fixed for any bug fixes.

Removed for now-deprecated features.

No Jargon: Keep descriptions simple so anyone reviewing your GitHub (like an employer) can understand your progress.
