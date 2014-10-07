# Hackathon 10/6 - Data Methods and Design

# Team Members

* [name-of-a-team-member](URL to this member's github account)
* [name-of-a-team-member](URL to this member's github account)
* [name-of-a-team-member](URL to this member's github account)
* [name-of-a-team-member](URL to this member's github account)
* [name-of-a-team-member](URL to this member's github account)

# Part 1: Data Science Fundamentals


## Q1: There are generally 2 situations you'll start from when approaching a question of data: a) You designed and collected the data yourself OR b) You have to work with a data set you've been given access to.  What do you think makes these 2 starting points different?  How might it change what analysis you'll do?
- what am i looking at
- relationship between data

(For the following set of questions we'll assume we're in situation A - you are going to design your own data collection)

## Q2: What factors go into deciding what data format to use?  Under what circumstances may you use different data types?

JSON - nested data, sub classifications, 
CSV (SQL) : data base realtions between columns -- faster, joins across columns
Key-Value Store: can be very fast, computations that are expensive are routed to this format
txt documents

## Q3: Once you've chosen a format, you'll need to determine fields to capture and store.  A common approach for this involves determining what QUESTIONS you want to ask of your dataset.  For the following examples, please respond with which field(s) your may need to answer the questions needed:
1. You're working for a company that tracks data on public transportation, you know you'll want to be able to ask "What percentage of a time is a bus/train late?"
2. You're working for a school district, and you need to be able to help the principal answer the question "Which teachers are most successful at getting students interested in extra-curricular educational activities (e.g., Math Team, Quiz Bowl, Science Olypiad, Robot Building, etc)? 
3. You're starting a social networking website that helps friends choose what to do on a Friday night, and you need to be able to answer the question, "Who made the suggestion that led to the final decision?"

### Answers:
1. actual arrival time, estimated arrival time
2. 
3. [comments with author, timestamps?, ]  

## Q4: Now you need to decide how you'll query your data.  What are the costs and benefits of the following options: 
1. Store the data raw and load it into a Python or JavaScript Shell for analysis.  
2. Periodically dump the data into a database (like Mongo) and query it.
3. Build a webserver and write an API that dumps and queries that data in your database.

### Answers:
1. 
Costs: not scaleable
Benefits: fast
2. costs: application and database are very closesly intertwind
benfits: 
3.
Costs: hackable
Benefits: easily assasable, public access


## Q5: You've now set up your database and have a website with 10,000 users, but have realized that you forgot a much needed field (say, an ID number for each user).  What do you do and how might different database designs have helped this situation?



---------------

(For this section, you may need to do some online research to answer the questions.)

## Q6: What is a Baysian Classifier?  What is it used for?

what is the probablity it is or is not x
niave: every event(data) as indepdent
bayes - determains probablity 

## Q7: What is a simple graph you could generate to check for outliers in a dataset?
scatterplot
histogram

## Q8: What is a Null Hypothesis?
hypothesis that two data sets have no corrilation 

----------

Answer the following questions using this scenario: You just got a HUGE dataset from Spotify where each entry contains these fields -> [username, song, # of times played, user rating, genre]

## Q9: How would you figure out the most popular song?
- most frequently played, and high user rating
- what song has most distinct users

## Q10: How do you determine what genre a certain user likes the most?
- user rating

## Q11: How do we match 2 users that we think may want to share playlists?
- common enjoyed genre

## Q12: What assumptions would you have before digging into Spotify data?  How would you test them?
[Response]
- what do you think is true about data set
- what do you think is interesting

----------

Answer these last questions generally.

## Q12: What is a correlation and how do you find them in a data set?
- two variables that are related to eachother/are dependent
- co-variance 
- regression model

## Q13: How can correlations help us tell a story with our data? 
biggest tool in proving/validating a hypothesis

## Q14: Let's think about data science as a way to tell a story about some data.  Why would I want to bring a second data set into my story?

adds complexity to ones story

## Q15: This one's just for fun.  How percent of the time do you expect to actually get the result you wanted?
- 99% of the time


# Part 2: Analyzing Your Data

While there are many tools to do this analysis, we will use the JS library Gauss to accomplish this task since everyone should have used it by now.

## Screenshot of Data in Gauss
![screenshot of data in gauss](image.png?raw=true) 

## Most Frequent Value
[cut and paste command used and the output it produced]

## Range of data
[cut and paste command used and the output it produced]

## Biggest Change
[cut and paste command used and the related snippet from the output]

## Shape of data
[Describe]

## Threshold
[Value]

## Percentage above/below
[Command and output]

## Yes/No + Justification
[Answer and any images/snippets to justify]

# Part 3: Project Design Exercise

## Link to the device or devices you're interested in using
* [device1](URL to this device)
* [device2](URL to this device)

## What it would measure and how?
[Response]

## Where you'd put it in the lobby?
[Location]

## What problems could threaten the validity of your data?
[Response]

## How often to sample and when to make a data dump?
[Response]

## Resulting viz.
[Describe or link to example]

## Timing trigger
[Necessary? Why? and How?]

