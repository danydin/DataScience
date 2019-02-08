espn nba standing scraper puesdo code:

# 1 #### Importing Modules 
load requests to open url
loads bs4 to parse the source

# 2 #### Setup to Scrape Data from ESPN NBA Standings 2017-2018 using BeautifulSoup 
load url through requests 
parse url through BeautifulSoup
findAll on the element that covers all names & statistics

# 3 #### Getting Team Code and Team Names 
creating empty list to store the teams
choose the specific INDEX object which covers the teams list only from the findALL object created on chapter 2 
loop through each element in the that object ^
assign var to the element .text with the code-name of the team
assign var to the element .text with the full-name of the team
append those 2 vars to the empty list created above inside a tuple
* this part will loop through all teams and append their names and code-names to the empty list

# 4 #### Getting Stats for Each Team
create list to store statsitcs of the teams
find the element covers all the stasitics
findAll table row elements which cover statsics and then loop through them
var for findAll the specific table data in the loop (the cell/column)
append each column .text according to what it scrape to it coorelate var (won,lose,percent, etc - 13 vars in total)
append all the vars in a tuple in the loop to the statsics empty list

# 5 #### Combine Teaminfo and Teamstats to create single list for each team with Labels
take the 2 main vars from the last 2 chapters and zip them into 1 list 
create var for thr 10 labels of the second main var for the excel sheet

# ## Importing data into Pandas DataFrame



