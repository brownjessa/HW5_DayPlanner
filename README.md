# HW5_DayPlanner
# 05 Third-Party APIs: Work Day Scheduler

Create a simple calendar application that allows the user to save events for each hour of the day. This app will run in the browser and feature dynamically updated HTML and CSS powered by jQuery.

You'll need to use the [Moment.js](https://momentjs.com/) library to work with date and time. Be sure to read the documentation carefully and concentrate on using Moment.js in the browser.

## User Story

```
AS AN employee with a busy schedule
I WANT to add important events to a daily planner
SO THAT I can manage my time effectively
```

## Acceptance Criteria

```
GIVEN I am using a daily planner to create a schedule
WHEN I open the planner
THEN the current day is displayed at the top of the calendar
WHEN I scroll down
THEN I am presented with timeblocks for standard business hours
WHEN I view the timeblocks for that day
THEN each timeblock is color coded to indicate whether it is in the past, present, or future
WHEN I click into a timeblock
THEN I can enter an event
WHEN I click the save button for that timeblock
THEN the text for that event is saved in local storage
WHEN I refresh the page
THEN the saved events persist
```

The following animation demonstrates the application functionality:

![day planner demo](./Assets/05-third-party-apis-homework-demo.gif)

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.

- - -
© 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.


Steps:

HTML:
1. Set up html to function properly and link to script.js
2. Start making timeblocks using columns, rows, and div ids that will appropriately function in js and css. Include save buttons in those timeblocks. 

Java/jsQuery:
3. Start writing javascript.
4. Display date function
5. On-click function for save buttons for each time block.
6. Function to save event with schedule array, store appointments, remove appointments previously scheduled at same time as new appointment, update local storage.
7. Add schedule to html within script.js
8. Create variables to change colors of rows
9. Function to change color of rows per hour that updates every second
10. Add function to keep colors of rows the same outside of work hours


Link to the page:
 https://brownjessa.github.io/HW5_DayPlanner/
