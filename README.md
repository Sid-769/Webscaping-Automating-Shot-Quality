# Convex Hull Shot Analysis using Webscraping

## Project Overview
This project leverages **Convex Hulls** and advanced football analytics to visualize and analyze player shot data from open play. By combining automated data scraping and shot quality metrics, the project aims to provide a comprehensive view of a player's shooting efficiency and spatial tendencies on the pitch.

## Features
- **Automated Web Scraping**: Scrapes shot map data for players from online sources (e.g., Fotmob), significantly reducing manual effort.
- **Shot Data Preprocessing**: Filters and structures shot data, focusing on "RegularPlay" and "FastBreak" scenarios.
- **Convex Hull Analysis**: Uses Convex Hull to highlight the range and distribution of a player's shots.
- **Visualizations**:
  - Plots shot locations and Convex Hulls on a half-pitch diagram.
  - Includes a color-coded **Shot Quality Meter** to represent shot effectiveness, where blue tones indicate higher quality.
- **Performance Metrics**:
  - Calculates key stats like Expected Goals (xG), Expected Goals on Target (xGOT), Shot Quality, and Conversion Rates.
  - Displays player-specific stats alongside visualizations.

## Getting Started
### Prerequisites
- Python 3.x
- Required libraries:
  - `numpy`
  - `matplotlib`
  - `scipy`
  - `pandas`

Install dependencies via:
```bash
pip install numpy matplotlib scipy pandas
```

### Usage
1. **Run the Notebook**:
   - Load the provided `.ipynb` file.
   - Follow the cells to scrape data, process shot points, and visualize results.

2. **Customize for Players**:
   - Update the player name and season to analyze data for different players.
   - Automatically generate visualizations and performance summaries.

3. **Integration**:
   - The backend can be integrated with a frontend where users input player names and seasons to get dynamic visualizations.

## Files
- `ConvexHullWSFinal.ipynb`: Main notebook containing code for web scraping, data analysis, and visualization.
- `requirements.txt`: List of required dependencies.

## Future Development
- **Full Automation**: Automate web scraping for multiple players across seasons.
- **Web Application**: Develop a frontend to allow users to input player names and seasons, with real-time visualizations and stats.
- **Comprehensive Metrics**: Incorporate more advanced football analytics like pass maps and defensive actions.

## Contributors
- **Siddharth Singh** – Developer and Researcher

## License
This project is licensed under the MIT License.
