# WebScrappingMars-M11-Challenge

Intro
This challenge takes on web scrapping that extracts information via both automated browsing with Splinter and HTML parsing with Beautiful Soup on Mars news and temperature. 

Part 1 - Scrape Titles and Preview Text from Mars News
This section utilized Splinter and Beautiful Soup to scrap data from Mars news website. The part_1_mars_news notebook uses auto browsing to create a browser object using splinter. Next step is to read the website by creating beautiful soup object to 
extract text elemtnts from the website. From there, the titles are isolted and stored in dictionaries list and then printed in the notebook adn dumped into json file. 

Part 2 - Scrape and Analyze Mars Weather Data
This section analyzes data by utilizing Splinter, Beautiful Soup, Pandas, and Matplotlib to scrape Mars Temperature Data. 

For this part, the analyzed data answers the following questions:
-1)How many months exist on Mars? ANS: 12

-2)How many Martian (and not Earth) days worth of data exist in the scraped dataset? ANS: 1867

-3)What are the coldest and the warmest months on Mars (at the location of Curiosity)? 
- Coldest Month: (3) | Warmest month: (8)
-Plot the results as a bar chart.

![image](https://github.com/ashmmaryo/WebScrappingMars-M11-Challenge/assets/146042131/a21adb5d-d538-4c32-979f-607d876ca0b7)

-4)Which months have the lowest and the highest atmospheric pressure on Mars?
-Lowest Atmospheric pressure: (6) | Highest Atmospheris pressure: (9)
-Plot the results as a bar chart.

![image](https://github.com/ashmmaryo/WebScrappingMars-M11-Challenge/assets/146042131/57c18471-8192-4258-a084-019b27fe58b0)

-5)About how many terrestrial (Earth) days exist in a Martian year? 
-The distance from peak to peak is roughly 1425-750, or 675 days. A year on Mars appears to be about 675 days from the plot. Internet search confirms that a Mars year is equivalent to 687 earth days.
