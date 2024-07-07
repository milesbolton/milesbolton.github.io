# Analyzing New York Mets' attendance
### What I aimed to accomplish
I wanted to find out why the New York Mets have seen a <a href="https://milesbolton.github.io/lede-project-1/mets-2024-attendance-fans.html">sizable drop in attendance</a> this season — the most of any MLB team. This issue was widely covered by local media outlets early in the season, and as of June 30, 2024, the Mets are still averaging over 6,000 fans less at home games this season compared to 2023 games.
I also went to the Mets' June 28 game against the Astros to take pictures and get information I needed to describe the scene of the game.

### Description of my findings
I did confirm that the Mets' league-leading attendance drop moved then from ninth in league attendance in 2023 to 19th in 2024.
Historically, the Mets' attendance has been heavily tied to success. I found this out by tracking their attendance over their history, and discovered that their attendance typically peaks in one to two seasons following a deep playoff run in which they played in the NLCS or World Series.
The Mets' franchise attendance record was in 2008, when they played their final season at Shea Stadium. They had played at Shea Stadium since 1964.
The Mets have seen capacity crowds for three home games this season: Opening Day and the two Subway Series games against the New York Yankees. These three games were the top-three attended home contests of the Mets' 2023 season.

### Summary of my data collection process
I found all of my data on <a href="https://www.baseball-reference.com/">baseball-reference.com</a>, where I filtered out road games and games that had not yet been played this season, then downloaded my data in CSV format.
The data sets I looked through were 2024 Mets games, 2024 MLB attendance by team, Mets' historical attendance and league payroll.
I used Pandas to look through and clean up my data. Then, I used Datawrapper to put together my charts, highlight specific ranges and sort my data how I wanted to.

### Overview of my data analysis process
See "Description of my findings" and "Summary of my data collection process" above for details on how I analyzed my data.

### Skills and approaches I used, where I grew most during the project
This project helped me become more comfortable with working with data sets in Pandas. I became more familiar with using the internet and Stack Overflow to find the right commands for what I wanted to do, and then figuring out how to use these in my own notebook.
One specific example of this was when I wanted to combine two columns in my 2024 Mets attendance by game data. I wanted to combine the 'date' and 'opponent' columns into one, so I could represent each specific game in one column.

### Things I tried or wanted to do, but did not have the skills or time to
This is my first ever data analysis project using Pandas, so I'm pretty happy with what I was able to accomplish. I would have loved to dive into what, other than winning more games, the Mets could do to boost attendance since it's commonly said among local baseball fans that Citi Field has a much better game day experience than Yankee Stadium. 
If the project had a later due date, I would like to see if the summer tourist season influenced attendance at all.
