
# Ottoman Buildings Dataset

## Category
Buildings designed by Ottoman architects (Wikipedia categories)

## Research Question
How are buildings designed by major Ottoman architects geographically distributed and how long did their construction take?

## Data Source
All data was collected from Wikipedia pages belonging to categories related to Ottoman architects and their buildings.

## Data Collection Method
Data was collected using a web scraping approach with Python. The process followed standard politeness rules, including rate limiting (2 seconds delay between requests). Information was extracted from Wikipedia infoboxes of building pages.

## Dataset Description
The dataset contains information about buildings designed by Ottoman architects. Each record represents one building and includes architectural, temporal, and spatial attributes.

## Variables
- building_name — Name of the building
- architect — Architect who designed the building
- building_type — Type of the building
- location — Location of the building
- latitude — Latitude coordinate
- longitude — Longitude coordinate
- construction_start — Year construction started
- construction_end — Year construction completed
- construction_time — Construction duration in years
- renovation_date — Year of renovation or restoration if available
- wikipedia_url — Source Wikipedia page

## Files Included
- dataset.pkl — Final dataset in pickle format
- dataDictionary.json — Description of variables
- metadata.json — Dataset metadata
- requirements.txt — Python libraries used
- ottoman_buildings.csv — CSV version of the dataset
