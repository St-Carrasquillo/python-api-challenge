# python-api-challenge
Module 6 WeatherPy challenge

## Part1: WeatherPy
Data's true power is its ability to definitively answer questions. So, let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?"

Now, we know what you may be thinking: “That’s obvious. It gets hotter.” But, if pressed for more information, how would you prove that?

Findings: 
1. In both the northen and southern hemisphere, the further away from the equator (0) a city is, the lower the max tempature is.
2. In the northen, the closer to equator (0) a city is, the lower the Humidity is while the opposite is true in the southern hemisphere.
3. The r-value of 0.266 in the northern hemisphere and 0.269 in the southern hemisphere indicates a strong linear relationship between Cloudiness and Latitude.
4. The r-value of -0.0709 in the northern hemisphere and -0.4053 in the southern hemisphere indicates a moderate linear relationship between Wind Speed and Latitude.


## Part2: VacationPy
In this deliverable, you'll use your weather data skills to plan future vacations. Also, you'll use Jupyter notebooks, the geoViews Python library, and the Geoapify API.

The code needed to import the required libraries and load the CSV file with the weather and coordinates data for each city created in Part 1 is provided to help you get started.

### Hotel Output
I experienced issues with the code for locating the nearest hotels but realized it was because I had made too many requests in one day and needed to narrow down my results. So I chose to filter to specific countries with a cloudiness reading less than 25 and wind speed lower than 7. That brought back 17 results and all but one had a hotel within 10,000 meters.

