# Homework 5

This is the 5th homework for the coding bootcamp

### Summary
* HTML and CSS and Javascript documents create a day planner with an eight-hour work day
* The task manager aspect saves entries to local storage
* This project emphasizes the use of using Javascript to save and retrieve data from local storage
* This project utilizes the use of moment.js for time calculation and formatting  conversion 

### This project has the following features: 
* A header with local time that updates live
* Seven Input Entries
* A Save button that saves items to local storage
    * Attribute changes for hour by hour time tracking 
    * Gray is past the current hour
    * Red is on the current hour
    * Green is before the current hour
    
### Psuedo code:  
* Find out of Moment.js needs further installation
* Start with Document onload
* Look up Javscript Calendar, write steps down and find matching Jquery methods
* Variables unknown until step above is complete
    ** Needs start time
    ** Needs end time
    ** Needs current time  
    ** Needs to compare each hour to current time, and determine if it is 
    ** Current time is always going to be more than start time
    ** Current time is always going to be less than end time
    ** Difference between the two
    ** For loop for starting time, it would only be able to loop up to the ending time, then what?
    ** How can we use moment duration to compare time?

### This project has script features of:
* Moment.js for local time, current time, and time conversion for individual hours
* Appended text to HTML for hour time
* If, if/else statement to compare time with the current time 
* Appended attributes for color current time 
* An event listener for the save buttons to save to local storage

### This project features responsive design using a Bootstrap layout
### Has responsive layout for: 
** Small devices (landscape phones, 576px and up)
** Medium devices (tablets, 768px and up)
** Large devices (desktops, 992px and up)
** Extra large devices (large desktops, 1200px and up)

### To Execute File:
> Open in browser


## Demo
![Day-Planner Demo](Day-Planner.gif)

## Links to deployed page
* [Deployed page](https://anirbantalukder.github.io/homework_5/)
* [Github repo](https://github.com/AnirbanTalukder/homework_5)
