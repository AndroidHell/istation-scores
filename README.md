  _  _____ _        _   _                _____                         
 (_)/ ____| |      | | (_)              / ____|                        
  _| (___ | |_ __ _| |_ _  ___  _ __   | (___   ___ ___  _ __ ___  ___ 
 | |\___ \| __/ _` | __| |/ _ \| '_ \   \___ \ / __/ _ \| '__/ _ \/ __|
 | |____) | || (_| | |_| | (_) | | | |  ____) | (_| (_) | | |  __/\__ \
 |_|_____/ \__\__,_|\__|_|\___/|_| |_| |_____/ \___\___/|_|  \___||___/
                                                                       

## Project Overview
+ written in HTML and JavaScript
+ Abusing a "front-end" PHP file so I can host it - just redirects
+ Use is for calculating reading scores for students to assess if the yare behind or not
+ The goal was to help automate my wife's job a bit.
+ Might add mor features later
+ Simple interface done with a bit of Bootstrap
+ Table styled with straight CSS
+ Main algorythm was written with a ton of help from IceSoldier/QuietMisdreavus

## Functionality
+ Simply displays first three columns and students scores
+ Calculates where they should be by current month
+ If they are at around the month's score, gives an "OK"
+ If they are behind by 4 or more months, calculates what they need to achieve to cactch up

##TODO:
+ Calculate how much per month a student who is behind should be progressing
+ Calculate how much per month a student who is ahead should be progressing
+ Possibly export table as a .xlsx or .csv file
+ If I make a series of tools, include the mall in a webapp with menu links