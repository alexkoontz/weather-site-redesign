# Weather Website Redesign
**Date:**  October 2019 - Ongoing

**Organization:** Penn State University

**Project Members:** Myself, and Joe Royer (Assistant Director of IT at Penn State York)

**[Penn State York Weather Site](http://weather.york.psu.edu/)**

![](https://github.com/alexkoontz/weather-site-redesign/blob/master/rdme_src/weather_screenshot_1.png)


## Problem Description
Joe Royer requested that I develop and redesign a website.  This website shows data from a weather station located at the Penn State York campus.  The previous design was outdated and needed to be refreshed to fit Penn State's branding and color scheme.  It should also display the data clearly and have the most important data on the main page.  The last detail was for it to be mobile-friendly.  
## Brainstorming
My initial steps were to use a front-end framework to give me the styling and mobile responsiveness I needed.  I decided to use Bootstrap 4 as I was very familiar with the grid-based layout used to structure pages.  For styling guidance I referenced another Penn State York website for [Student Activity Fees](http://saf.york.psu.edu/).  I also viewed many weather websites for ideas on how to present the data effectively. I was then able to analyze how I would receive the data, which would require JavaScript (jQuery) since the incoming data was in a JSON format.
## Steps

### Design
The original design of the website:

![](https://github.com/alexkoontz/weather-site-redesign/blob/master/rdme_src/screengrab_1_main_page.PNG)

First draft of the redesign:

![](https://github.com/alexkoontz/weather-site-redesign/blob/master/rdme_src/draft_1.PNG)

Using comical placeholder data, I focused on the layout and visual styling for the redesign.  I chose temperature to be the largest and most important piece of data on the home page, with a "Feels Like" temperature right below it.  The data to the right of the temperature section would have more detailed data for the current day in a table format.  This table is very similar to the previous design's, but adapted for the new visuals.  

Second draft:

![](https://github.com/alexkoontz/weather-site-redesign/blob/master/rdme_src/draft_3.PNG)

I began to change details about the design, like font size, proper grid alignment, and bolded headers for the table sections.

Final design:

![](https://github.com/alexkoontz/weather-site-redesign/blob/master/rdme_src/weather_screenshot_1.png)

The final design features a stylish and functional navigation bar, with two clear data sections on the main page.  These design concepts were used on the other pages that present weather data in a gauge format (a JavaScript library reused from the previous website, [drawn with SteelSeries and scripted by Mark Crossley](https://cumuluswiki.org/a/SteelSeries_Gauges)):

![](https://github.com/alexkoontz/weather-site-redesign/blob/master/rdme_src/weather_gauges_redesign.png)

As well pages showing monthly, yearly, and other various records:

![](https://github.com/alexkoontz/weather-site-redesign/blob/master/rdme_src/monthly_redesign.png)


## Deployment

This site was deployed incrementally through a series of updates to the live website.  I know this was not a professional way to update a live website as it would interrupt and confuse users.  The URL was not known to the public which is why the live site was updated and used as the development environment.  An ideal environment would be a virtual machine that is identical to the server the website will be hosted on.  This means the same version of Linux, Apache, and any other software being used.  In future projects I will use this method to develop.

## Conclusion

This project challenged me to trust my judgment with design and I am very happy with the final product.  It was also beneficial to work with the data transfer from the server hosting the weather station to the website's server.  Using JSON data I was able to have the website update weather data every minute without needing to refresh the page.  Joe Royer was very pleased with the result.
