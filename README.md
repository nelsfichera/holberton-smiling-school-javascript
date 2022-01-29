# 0x0F. Build a web app in JavaScript

## Requirements
> You have to use Bootstrap
> Your styles.css must be as small as you can - you must use as much as you can Bootstrap classes
> You have to use JQuery
> Your scripts.js must contain all your Javascript part
> Your Javascript must be executed only when the document is loaded
## Imports
> For this project, you will need: fonts from Google, JQuery, Bootstrap CSS/JS
## Interactions note:
> Web pages must switch to the tablet version when the screen width is 768px
> Web pages must switch to the mobile version when the screen width is 576px
> button hover/active: opacity: 0.9

Final screens @ ./final-screens

### 0. Reuse and polish your Bootrstrap integration
> Copy previous files (homepage>0-homepage, etc.)
> Create a Readme

### 1. Homepage - quotes
From 0-homepage.html, create 1-homepage.html.

> Replace static quotes by dynamic loading:

> URL: https://smileschool-api.hbtn.info/quotes
> No static quotes should be present in the quotes section
> During the Ajax request, a loader should be present
> Carousel should work like before

### 2. Homepage - popular tutorials
From 1-homepage.html, create 2-homepage.html.

> Replace static video cards by dynamic loading:

> URL: https://smileschool-api.hbtn.info/popular-tutorials
> No static video cards should be present in the section
> During the Ajax request, a loader should be present
> Carousel should work by sliding card by card (like GIF below) - this kind of carousel is not unique, make it generic to reuse it easily!
> Don’t forget the responsive part!

### 3. Homepage - latest videos
From 2-homepage.html, create homepage.html.

> Replace static video card by dynamic loading:

> URL: https://smileschool-api.hbtn.info/latest-videos
> No static video cards should be present in the section
> During the Ajax request, a loader should be present
> Carousel should work by sliding card by card (like GIF below) - this kind of carousel is not unique, make it generic to reuse it easily!
> Don’t forget the responsive part!

#### 4. Pricing - quotes
From 0-pricing.html, create pricing.html.

> Replace static quotes by dynamic loading:

> URL: https://smileschool-api.hbtn.info/quotes
> No static quotes should be present in the quotes section
> During the Ajax request, a loader should be present
> Carousel should work like before
> Same as the homepage.html

#### 5. Courses
From 0-courses.html, create courses.html.

> Replace static video card by dynamic loading:

* URL: https://smileschool-api.hbtn.info/courses
    * GET parameters:
    * q: search value (in our case, the value of the field KEYWORDS)
    * topic: topic filter value (in our case, the value of the field TOPICS)
    * sort: order of all courses (in our case, the value of the field SORT BY)
> No static video cards should be present in the section
> During the Ajax request, a loader should be present
* Dropdowns are dynamic (coming from the API):
    * Topic: list of topics
    * Sort by: list of sorts
> Search value should be initialized by the value q in the API response
> The list of video cards is coming from courses in the API response
* API request must be done when:
    * Search value is changing
    * A new Topic is selected
    * A new Sort by is selected

#### 6. JSON to XML
> Convert all your JSON Ajax call to another API… a XML API!

* Copy files - same content, except loading xml-scripts.js instead of script.js
* homepage.html -> xml-homepage.html
* pricing.html -> xml-pricing.html
* courses.html -> xml-courses.html

And use this API:
* quotes: https://smileschool-api.hbtn.info/xml/quotes
* popular tutorials: https://smileschool-api.hbtn.info/xml/popular-tutorials
* latest videos: https://smileschool-api.hbtn.info/xml/latest-videos
* courses: https://smileschool-api.hbtn.info/xml/courses
Final result should be the same as the JSON API version