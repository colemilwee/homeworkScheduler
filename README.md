# homeworkScheduler
in this homework i have to make a scheduler based on time from 9am to 5pm and save local data if its past a time its grey if its current its red and if its in the future its green
i first make the html layout for 9am to 5pm and the buttons as well with there own ids for later and text area so they can write in there plans
then under script i write my java the first thing it does is load local storage data if they already saved data 
the next line of code pulls the current date, year, and time from the machine its running from
what happens next is i make an array for the hours with the ids i used earlier and after that i use a for loop to make it color the past present and future with <, ==, and >
i made click events for every button using the ids and give it a function that links to a function to seperate them
the next thing that happens is a case switch so that each calendar button can save the text in the right area
and last is the local storage that sets the item
