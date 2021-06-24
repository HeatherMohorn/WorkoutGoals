# Workout Goals
#### Video Demo:  <https://www.youtube.com/watch?v=mpSi7Kmp8yY>
#### Description:
Workout Goals is a web app that allows the user to track exercise and progress towards a goal.

Background- In 2012, I challenged myself to work out for 366 hours over the course of the year. Sometimes I do a 2-hour swim practice, sometimes I sit around all day, but it had to add up to 366 hours by 12/31/12.

It took a long NYE workout, but I did it! And then I did it again in 2013. Then I just kept doing it every year. In 2017 I did it pregnant and decided that labor counted on 12/30. In 2020, did it with a toddler while pregnant during a global pandemic, so
at this point I'm planning to keep going forever.

I've been using a spreadsheet to track this data for almost 10 years. Now I am building something more sophisticated. This web app gives me the data that is interesting to me. It allows others to track their workouts and progress as well.

I plan to expand this as I learn new things. This is my minimum viable product. I am going to take more classes to add more features as I go. The about page has some ideas of future improvements.


HTML files-
index: Here is where we gather user input. The date menu defaults to today. Users have a list of sports in a drop-down menu. They can add a sport if it's the first time entering it into the log. They can enter duration, distance, and notes if desired.

data: The default goal is to exercise 365 hours over the course of a year. The data page shows the total hours so far, days elapsed, days to go, percent progress, and how many minutes per day you must average to meet the goal by end of year.

apology: Gives error message for invalid input.

about: This page gives the background on why I created this app. I'm on my 10th year of tracking all of this information with a spreadsheet, and it's about time for something for sophisticated!

layout: I wanted a clean layout that would be easy to read. I used bootstrap to create an appealing and simple site. I used jinja and blocks to cut down on redundancy on other pages.

log: This displays a clean table of each workout entry, including date, activity, duration, distance, and notes. It queries the SQL database to list all of the workouts for that user, ordered by date.

login: Log in with username and password. Invalid entries lead to error messages. Users are stored in the SQL database workouts.db in a table called users.

register: Users can create a username and password. Invalid entires lead to error messages.


Data is stored in workouts.db, a database with 2 tables, users and workoutList.

Upcoming features:
Data visualization
Animation for reaching goals
Customizable user settings
Analysis by sport
Custom goals
Allow users to edit their data
