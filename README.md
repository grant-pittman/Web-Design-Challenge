# Web Visualization Dashboard - Web-Design-Challenge <!-- omit in toc -->

- [Background](#background)
- [Website Layout](#website-requirements)
- [Navigation Layout](#navigation-requirements)


## Background

Data is more powerful when we share it with others!  In this assignment, I am taking the visuals from the Python-API challenge, and using HTML, CSS and bootstrap to create a dashboard to show it off! 


## Website Layout

The website consist of the seven pages total, including:

* A [landing page] containing:
  * An explanation of the project
  * Links to each visualization page.

* Four visualization pages:
  * [Latitude vs Temperature]
  * [Latitude vs Cloudiness]
  * [Latitude vs Humidity]
  * [Latitude vs Wind Speed]
  * Each of these pages contains:
    * A descriptive title and heading tag
    * The plot/visualization itself for the selected comparison
    * A paragraph describing the plot and its significance.

* A ["comparisons" page] that:
  * Contains all of the visualizations on the same page so we can easily compare them.
  * Uses a bootstrap grid for the visualizations.


* A ["data" page] that:
  * Displays a responsive table containing the data used in the visualizations.

## Navigation Layout

The website contains a navigation menu at the top of each page that:

* Has the name of the site on the left of the nav which allows users to return to the landing page.
* Contains a dropdown on the right of the navbar named "Plots" which provides links to each of the visualization pages
* Provides two more links on the right: "Comparisons" which links to the comparisons page and "Data" which links to the data page

