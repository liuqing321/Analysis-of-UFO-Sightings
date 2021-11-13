# Analysis-of-UFO-Sightings

## Overview of Project 

The purpose of this project is to build a webpage that allow users to filter for multiple criteria at the same time. Filters for city, state, country and shape will be added to the webpage. 

## Instruction for Using the Webpage 

The table in the webpage contains all the information in data.js. To filter the table by different criteria, enter the criteria information in the input boxes next to the table. 
The placeholders in the input boxes have provided examples for different criteria. The input value must be in the same format as the placeholders. After entering all the criteria, hit "Enter" on the keyboard. The table will update accordingly. 

![result](https://user-images.githubusercontent.com/88631769/141652605-9a7b3e7d-f242-41ae-8ec5-1c80181994ab.PNG)


## Summary 

* Drawback of this webpage. 
  
The format of the input criteria must be the same as what in the placeholders. if we enter the criteria in capital letters, the result will be empty because the filters don't recognize the criteria. 

* Recommendations 
  1. We could create the fuzzy query function. So the table will be updated regardless the format of the input. 
  2. we could use "keyup" instead of "change" in the event handler. So the table will be updated while we are typing in the keywords. 
