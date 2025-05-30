# Research Planner
A single-page HTML &amp; Javascript web app to plan a PhD or Research Project

## Download App (Version 1.1.2)
You can download the app as an HTML file here (right-click Download Linked File / Save As): 
https://github.com/ahelme/research-planner/blob/main/research_planner_1.1.2.html

## Instructions
Download the HTML file to your desktop, then open it in your web-browser of choice.

## Github Pages
Alternatively, you can access the app here on Github Pages (however, if others are using the app you may lose your data):


## Purpose: This is a Research Planner that allows users to manage research activities and elements with dates, progress tracking, and supervisor communication.
* 	The application is completely self-contained in this single HTML file - just save it and open in any modern web browser.
   
## Structure:
* Activities contain elements
* Each element has fields like chapter, days, notes, progress, dates, supervisor communication
* Data is stored in a researchData array
* Table is dynamically rendered

## Features
### Add/Delete Activity/Element: Green + buttons and red × buttons for full control
* Delete All button deletes all data

### Dates Features
* Research Start Date Field at top of page: Can be modified by user. Controls when your entire plan begins.
* Automatic Date Recalculation: The first activity will always start on your specified Research Start Date
* Data Persistence: The Research Start Date is now saved and restored with your data
* First Activity: Always starts on the Research Start Date you set
* Activity Reordering: When you drag an activity to the first position, it automatically uses the Research Start Date
* New Activities: If you create a new activity and move it to the top, it will start on the Research Start Date
* Cascading Dates: All subsequent activities and elements automatically recalculate based on this baseline
### 	Save and Load Functions:
* Save Data: copies data in .json format to the clipboard with instructions to save as .json
* Load Data: loads a .json file into the Research Planner, replacing existing data
### 	Supervisor tracking:
* Three colored columns for committee communications
### 	Drag handles:
* Blue for activities, grey for elements
* Final three columns have colours automatically applied when data is added manually


![Research-Planner](https://github.com/user-attachments/assets/6ee4bb6c-d9a6-4bad-a281-9622f2da1d87)
