# Lab: Creating a Markdown Document

## Instructions
Please work in pairs: this assignment uses the University of Virginia men's basketball team's amazing 2019 season as an example, so if you are not a basketball fan please pair up with someone who is. For this lab, you will create a markdown document in R Studio. Remember, the purpose of a markdown document is to weave text, code, and results together into one document that is as visually appealing as possible. Please do the best job you can to produce a professional document that accomplishes the following tasks:

1. Open a new markdown document, choose HTML as the output, and title it "2019 UVA Men's Basketball Season Review". 

2. Make sure the document has a table of contents that floats along the side of the document.

3. Choose a theme other than the default theme for the document. Any theme that you like is fine.

4. Create the following sections and sub-sections:

* Season Recap
        
* My Experience of the Season
        
  * What Games I Went To or Watched During the Season
                
  * Two Photos That Illustrate the Season
                
* March Madness
                
* UVA Men's Basketball Players
        
  * Roster
                
  * Team Statistics (with tabs for the following sub-sections)
                
    * Offense
                        
    * Defense
    
  * Points vs. Rebounds
                        
5. Under Season Recap, write one paragraph summarizing the season. It was an exciting season, so make some words **bold** and others *italicized*. Tell us where you where when the Cavaliers won it all.

6. Under What Games I Went To or Watched During the Season, create a list (either numbered or unnumbered is okay) with the games you went to, or remember seeing on TV. Underneath each item in this list, create a sub-item that tells us if the Cavaliers won or lost the game, or if you can't remember.

7. Under Two Photos That Illustrate the Season, find two photographs online that represent some aspect of the season you would like to tell us about. Find the URL for the photo and link to it in your markdown document so that it appears directly in the document. Write a few sentences to tell us what you would like us to know about each photo.

8. Under March Madness, create a table with one row for each game of the March Madness tournament, a column for the date of the game, a column for the higher seeded team, a column for the lower seeded team, and a column for the score. Make sure it is a neatly formatted table in the markdown output.

9. Under UVA Men's Basketball Players, write a code chunk that loads the `tidyverse` and `knitr` packages. Use the options `warning=FALSE` and `message=FALSE` to suppress the messages that appear whenever you load `tidyverse`.

10. Under Roster, write a code chunk to load the "uva_roster.csv" file. Use `kable()` to create a neatly-formatted table to display the data. Write a sentence in this section that says: "There are X number of players on the team", where you fill in X by performing an in-line calculation of the number of rows in the "uva_roster.csv" data.

11. Under Team Statistics, create two clickable tabs: Offense and Defense 

12. Under Offense, create a table from the "uva_offense.csv" data and use `kable()` to display that table.

13. Under Defense, create a table from the "uva_defense.csv" data and use `kable()` to display that table.

14. Using the offense data, create a scatterplot with rebounds ("TRB") on the x-axis and points ("PTS") on the y-axis. Use the `fig.width` and `fig.height` options in this code chunk to control the width and height of this figure in your document.

15. Display your output in a web-browser.

16. Publish your output on RPubs. (You will need to create a free RPubs account)

