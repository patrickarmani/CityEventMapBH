# Overview

The purpose of this project is to learn how to integrate Geographic Information Systems (GIS) concepts with JavaScript and HTML. The application demonstrates how to visualize geographic event data using latitude and longitude coordinates, and how to provide interactive filtering and popup functionality within a web-based map interface.

This project fulfills the GIS Mapping module requirements by displaying at least 20 markers on a map and allowing users to interact with them.

# Software Description

his web application displays 20 city events located throughout Belo Horizonte, Minas Gerais, Brazil.

When the application loads, users see an interactive map centered on the city. Each event is represented by a marker based on its geographic coordinates.

The application includes:

A category filter (Music, Sports, Food, Tech, Culture, Education)

A text search field to search by event name

Interactive popups displaying:

Event name

Category

Date

Description

A live marker counter that updates when filters are applied

The project uses the official Esri CDN to load the ArcGIS Maps SDK for JavaScript:

https://js.arcgis.com/4.29/

Because the API is loaded remotely, the application requires an internet connection to function properly.

# The purpose of the software

The goal of this application is to provide an interactive GIS-based visualization of upcoming city events. Users can explore events geographically, apply filters, and access detailed event information through map interaction.

# Youtube link

[Software Demo Video](http://youtube.link.goes.here)

# Development Environment

Code Editor: Visual Studio Code

Operating System: Windows 11

Local Server: VS Code Live Server Extension

Browser for Testing: Google Chrome

# Language & Technologies

HTML5

CSS3

JavaScript (ES6)

ArcGIS Maps SDK for JavaScript (v4.29) loaded via CDN

OpenStreetMap Basemap

# Useful Websites

- [ArcGIS Maps SDK for JavaScript (Official Documentation)](https://developers.arcgis.com/javascript/)
- [ArcGIS CDN](https://js.arcgis.com/)
- [loaded the API using](https://js.arcgis.com/4.29/)
- [MDN Web Docs (JavaScript & HTML reference)](https://developer.mozilla.org/)
- [OpenStreetMap](https://www.openstreetmap.org/)

# Future Work

- Integrate a real-time public API or ArcGIS Feature Service to dynamically load event data.
- Implement category-based marker symbology for better visual differentiation.
- Improve responsive design and enhance the user interface for mobile devices.
