# Power_Ranking_Calculator
Calculates a fantasy football league's power rankings based on lists of team names separated by newlines


Take in between 4 and 10 .txt documents containing ten lines of strings 

***can not just take one week's worth of input, but a whole seasons by iterating over a set of directories (one per week) and their input files inside. this way it would be easier to track week over week stats***

the strings are names ordered from best (top) to worst ( bottom)

names will be alphabetical characters with no spaces and the first letter capitalized

numbers denoting rank will be optional


program reads these files and assembles an array for each one

the arrays contain the lists of names

dictionary of (string, int) is the final data structure. each name represents one of the strings, while the ints are the power ranking scores

a team given a first overall rating gets 10 points, second gets 9, etc

scores are tabulated from the input files and stored in the int pairs on the dictionary

power rankings are output highest to lowest


-----


ideas for expansion----
week over week change can be tracked
most first / last place votes per week and over the year 
more to come 
