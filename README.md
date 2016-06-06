# Beer
Tools to generate a portable database of brewery information.

# What does this do?
These scripts will pull data from brewersassociation.org for every brewery
in a given state or country, and format it into a CSV that is suitable for
general use.

# Why does this exist?
I was going on a road trip and wanted to visit some breweries. I located a
source of data, and whipped up this code to scrape it and get it into a
format I could import into Google Maps. Also, because beer.

# Usage
For one state: `./state.sh "New York"`

For all states: `./all_states.sh`

For one country: `./country.sh Belgium`

For all countries: `./all_countries.sh`

# Data
The script will create a file like `./archive/United_States/New_York/New_York_YYYYMMDD.csv`
with current data from the brewery search function on brewersassociation.org.
If any previous CSV files for the given location exist, you'll also get a diff
from the most recent version.
