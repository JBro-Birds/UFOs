# UFOs

## Overview of Project
The focus of this project is to learn JavaScript by creating a table to organize UFO sighting data that is stored as an array.  As part of this project I'll need to customize the webpage using storyboard methodology, Bootstrap and add several functional filters that will allow users to interact with the visualizations.  Filters need to be created to make the table fully dynamic and the table needs to be put into an HTML file for easy viewing.  The end users will be able to use the filtering functionality to search the data set on the webpage based on their needs.  

### Purpose
The purpose of this project is to enhance the filtering functionality for the end user so that a more in-depth analysis of UFO sightings can be performed with the data set.  In addition to the "date" filter provided in the initial web site build "city", "state", "country" and "shape" filters will be created and made available for the end user.  The enhanced filtering will give the end user the ability to fine tune searches to meet their analysis needs.

## Results

Next to the data table there are five filter criteria in which a user can use to further define their search; the filters are as follows: date, city, state, country, shape.  

![filters_webpage](https://raw.githubusercontent.com/JBro-Birds/UFOs/master/support_readme/filters_webpage.png)

The filters function in a manner that the user can choose a single filter or multiple filters for a given search. The user enters the filter/s values needed and then presses "enter" on their keyboard.  For example to filter on a single criteria such as UFO sightings in the state of Texas the user enters "tx" in the "Enter State" filter and presses "enters" on their keyboard.  This examples appears as follows:

![filter_tx_revised](https://raw.githubusercontent.com/JBro-Birds/UFOs/master/support_readme/filter_tx_revised.png)

To filter on multiple criteria such as UFO sightings in the state of Texas and the shape as light the user enters "tx" in the "Enter State" filter and "light" in the "Enter Shape" filter.  This example appears as follows:

![filter_tx&light_revised](https://raw.githubusercontent.com/JBro-Birds/UFOs/master/support_readme/filter_tx&light_revised.png)

*  To return to the full data set the user can refresh the webpage or remove the filter value/s and press "enter" on their keyboard.

## Summary

A drawback of the webpage is that the filter functionality is very basic.  The end user has to know the exact filter values to enter when filtering.  For example to filter on the state of Arkansas the user has to know the state abbreviation is "ar".  For the date filter only a single date can be filtered at a time.  Two recommendations to enhance the filtering functionality is to build in the ability for the end user to select a range of dates for a given search and for the other filters to function as drop-down selection fields for the end user to make selections with more ease.
