# Go Assignment - Joe Luhrman

## Directions 
Write a program in Go that generates n weeks of random temperature data (one temperature for each day of the week from 0-100 degrees), calculates the average temperature for each week, and then sorts the average temperatures for each week from lowest to highest (don't worry about week number labels for the averages). You should use
Go routines to generate the data for each week simulataneously and then calculate the average for each week simulatneously. 

The program should be able to generate, calculate the average of, and finally sort the averages of any number of weeks (n). The number of weeks can be hardcoded or a user input or whatever you want as long as it can be changed and the program still works. 

The program should output the raw data for each day of each week, the unsorted averages of each week, and the sorted averages of each week.

It's okay for the temperatures to be ints but obviously the averages will need to be floats. You also do not need to write your own sort (use "sort" package).

## Hints
I would strongly recommend using VS Code with the Go extension (you also need to download the current version of Go from the official site).
I would recommend you use slices to store the averages of each week because Go has fast built-in slice sorts.

## Submission
Just a .go file with your code. 
