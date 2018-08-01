Restaurant Reviews App - Project #6 - Stage 1
#### Udacity's Google Developer Challenger Scholarship - Front End Web Development

[![N|Solid](https://www.stoddard.consulting/images/logos/Udacity_logo_small.png)](https://www.stoddard.consulting/images/logos/Udacity_logo_small.png)

### Summary
***
Make a fully responsible and accessible design, ready for different sized displays and screen reader use, starting off with a static design.
Also, begin converting the project into a Progressive Web Application by caching some assets for offline use.

### Goal
***
This project aims to test each student's ability to implement responsiveness and accessibility rules - WAI-ARIA roles, focus, etc -, as well as a Service Worker.
- **Responsiveness** - the given starter code (static design) should be corrected using flexbox or grid, in order to make the app display correctly across a large span of different displays; no CSS framworks, such as Bootstrap, should be used.
- **Accessibility** - the given starter code (static design) should be correctly coded in order to ensure the latest WAI-ARIA roles are complied with and all properties and attributes are applied in order to have the app fully functional when using a screen-reader
- **Service Worker** - the Service Worker should be implemented to begin improving the starter code (a static design) into a Progressive Web Application (PWA).

#### Project specifications
***
##### Responsive Design
  - **Is the site UI compatible with a range of display sizes?**
  -- All content is responsive and displays on a range of display sizes.
-- Content should make use of available screen real estate and should display correctly at all screen sizes.
--An image's associated title and text renders next to the image in all viewport sizes.
- **Are images responsive?** 
-- Images in the site are sized appropriate to the viewport and do not crowd or overlap other elements in the browser, regardless of viewport size.
- **Are application elements visible and usable in all viewports?**
-- On the main page, restaurants and images are displayed in all viewports. The detail page includes a map, hours and reviews in all viewports.
##### Accessibility
- **Are images accessible?**
-- All content-related images include appropriate alternate text that clearly describes the content of the image.
- **Is focus used appropriately to allow easy navigation of the site?**
-- Focus is appropriately managed allowing users to noticeably tab through each of the important elements of the page. Modal or interstitial windows appropriately lock focus.
- **Are site elements defined semantically?**
-- Elements on the page use the appropriate semantic elements. For those elements in which a semantic element is not available, appropriate ARIA roles are defined.
##### Offline Availability
- **Are pages that have been visited available offline?**
--When available in the browser, the site uses a service worker to cache responses to requests for site assets. Visited pages are rendered when there is no network access.

#### Dependencies
***
- Starter code forked from [Udacity](https://github.com/udacity/mws-restaurant-stage-1).
- The map displayed on this project is from [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). You need to replace <your MAPBOX API KEY HERE> with a token from Mapbox. Mapbox is free to use and does not require any payment information.

#### Run the Restaurant Reviews App
***

To start using this project follow these steps:
1. Git clone this [repository](https://github.com/Negmah/mws-restaurant-stage-1.git).
In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer. 
2. In a terminal, check the version of Python you have `python -V`.
If you don't have Python, just visit Python's [website](https://www.python.org/) to download and install the software. It's that simple! :)
4. If you have Python 2.x, run `python -m SimpleHTTPServer 8000` to spin up a server
5. If you have Python 3.x. run `python3 -m http.server 8000` to spin up a server
6. With the server running, open the following link in a browser of your choosing: [http://localhost:8000/](http://localhost:8000/).

***
### Note about ES6

Most of the code in this project has been written to the ES6 JavaScript specification for compatibility with modern web browsers and future proofing JavaScript code. As much as possible, try to maintain use of ES6 in any additional JavaScript you write.

![N|Solid](http://res.cloudinary.com/negmah/image/upload/v1533090663/Screenshot_2.png)

***
### CREDITS
**- [Mohamed Riaad | Udacity's Tutor](https://github.com/MOhammedRiaad/) - Live PRoject WalkThrough as well as constant help and support provided for this project**
**- [Mohamed Shawky Bayoumi](https://github.com/MohamedShawkyBayoumi) for awesome help throughout the whole project and constant motivation**
**- RodrigoC for powerful debugging**