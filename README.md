# topo_div_football_teams
This repo presents my research on applying Topological Data Analysis on football data. 

## Python Notebooks:

packages.ipynb
Contains the installation commands for all required Python packages.

aggregate_statistics.ipynb
Queries all matches and statistics of the season and aggregates them by players.

Barcelona_aggregate_stats_seasons.ipynb
Queries all available Barcelona matches by seasons and aggregates player statistics.

Barcelona_aggregate_stats_coaches.ipynb
Queries all available Barcelona matches by coaches and aggregates player statistics.

Barcelona_aggregate_stats_per90.ipynb
Calculates the data from files 2 and 3 projected to 90 minutes.

torus_persistence.ipynb
Computes the persistence diagram and barcode of a torus. (Example)

top5_persistence.ipynb
Computes persistence diagrams of the top 5 leagues’ teams and visualizes the correlation between the mean of H_0 and the points gained.
Here, there is also the option to perform the analysis on multiple feature sets (via the selected_features variable).

PCA.ipynb
Computes persistence diagrams of the top 5 leagues’ teams based on all features, after dimensionality reduction using PCA.
PCA computes 4 principal components.
For each team, we saved the explained variance ratios and the principal components as well (in the {league}_PCA_all_features_avg_scalar folder).

Barcelona_persistence.ipynb
Computes persistence diagrams, time series analyses, and distance matrices of Barcelona’s seasons and coaching eras.
Here, there is also the option to perform the analysis on multiple feature sets (via the selected_features variable).

## Folders:

{league}_2015-2016
These folders contain all teams’ match-by-match and aggregated statistics.

BarcelonaSeasons and BarcelonaCoaches folders
These contain Barcelona’s aggregated match statistics, as well as persistence diagrams, time series analyses, and distance matrices by seasons and coaching eras.

4-5-dim and random
Contain the results of analyses performed according to alternative feature sets for the teams of the top 5 leagues.

{league}{feature set}{normalization}
Contain persistence diagrams calculated for the given league based on the specified feature set and normalization, along with the correlations between the mean of H_0 and the points gained.
