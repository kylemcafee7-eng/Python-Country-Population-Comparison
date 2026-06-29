This project was for a python class I took in college: 

For my final project I created a game in which the user will be asked which of two randomly selected countries (and territories) has a larger population. Once they give an answer they are told whether they were right or wrong and a bar graph will pop up to show the difference in population between the two countries. You earn one point for every right answer and at the end of the game the program saves your score if it happens to be a high score. 

I only created one class because I felt that there was really only one object in the game that really justified an entire class and that was the DisplayBoard which created the data visualization bar graph. 

I found a CSV online with data on all the countries in the world and their respective populations (it had more data than that, but I only used the countries and the populations for this) 

I tested my project continuously, slowly working out the bugs and finding ways to refine it, such as when I found out that the bar graph bases it’s scale on the larger population to prevent data from going off the charts and made it so the title updates based on the scale of population; since it’s always either an integer or a single digit float I made it so it would say “Population” if the scale was under a million, “Population (In Millions)” if the scale was between 1 million and 10 million, so on and so forth up to billions if you happen to pull China or India. 

For this project I need the random, json, csv and matplotlib/pyplot libraries. Random allows for randomization/random selection function calls, json allows the program to interact with json files, csv allows the program to interact with csv files and matplotlib has various data visualization function calls. 
