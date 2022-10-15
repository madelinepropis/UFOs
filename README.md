# UFOs

## Overview of Project

The purpose of this analysis was to help a data journalist, Dana, display UFO data onto a webpage. Dana is from McMinville, Oregon, where there have been many UFO sightings. She wants to write about these sightings in her town along with other reported sightings. She has a Javascript file with data about these UFO sightings, but wants to display them nicely as a table with filters.  

## Results

The HTML page displaying the results has various parts. The page is spread across twelve columns. 

![webpage](https://user-images.githubusercontent.com/109561408/195992574-391bf1fa-27f5-4c9d-9281-99493d670a27.png)

The top left has a "navbar" which says "UFO Sightings". When pressed, the page refreshes. 

![Navbar code](https://user-images.githubusercontent.com/109561408/195992581-3a695103-d33e-428b-9511-fd7aa534cc49.png)

Below the "navbar" there is a "jumbotron". This is basically the title for the page, where it states "The Truth is Out There" with a space-like background. 

![jumbotron code](https://user-images.githubusercontent.com/109561408/195992584-5416bbbd-774a-409c-89a0-b89697c9b5a3.png)

The next section is split into two: The paragraph title/subtitle and the actual paragraph. Since they spread across the same rows, but different columns, they are part of the same HTML "container-fluid", but the title/subtitle spreads across four columns and the paragraph spreads across eight columns. 

![container fluid code](https://user-images.githubusercontent.com/109561408/195992589-3e50b88b-0d32-4d88-8a36-11588dace4dd.png)

Similar to the previous section, the next section is split into two. The filter search for the data table is in the first three columns and the data table is in the next nine columns. The filters change the data based on the criteria. This is done by the JavaScript file which is called in the HTML file. 

![filter code](https://user-images.githubusercontent.com/109561408/195992596-ce3d4b4d-962e-4aae-a296-7b4a1716bba1.png)

![connection code](https://user-images.githubusercontent.com/109561408/195992612-f6a8a79a-6fb7-442a-a6f0-5e997cbf0339.png)

## Summary

One drawback of this new design is that there are no buttons included in the filter. I believe that a button makes the layout tidier and more precise. 

For further development, I would recommend that we have more data from other countries and other dates. The data we currently have only includes data from two weeks: January 1, 2010 to January 13, 2010. Additionally, I would recommend the webpage to include photos of these UFOs. The description explains it a well, but a picture is worth a thousand words. 

