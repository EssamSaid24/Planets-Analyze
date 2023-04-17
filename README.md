# Habitable Planets
This script uses the csv-parse and fs modules in Node.js to read a CSV file containing information about planets discovered by NASA's Kepler mission, and identifies the potentially habitable planets based on specific criteria.

#The criteria for identifying habitable planets are:

The planet's disposition is confirmed
The planet's insolation flux is between 0.36 and 1.11 times that of Earth
The planet's radius is less than 1.6 times that of Earth
The script then logs the number of habitable planets found, along with their names.
