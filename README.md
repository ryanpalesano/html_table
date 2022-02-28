# html_table

Create the following list of dictionaries and have it available for your route.

users = [
   {'first_name' : 'Michael', 'last_name' : 'Choi'},
   {'first_name' : 'John', 'last_name' : 'Supsupin'},
   {'first_name' : 'Mark', 'last_name' : 'Guillen'},
   {'first_name' : 'KB', 'last_name' : 'Tonel'}
]

Pass users to your template and have your template output an HTML table like this:

First Name	Last Name	Full Name
Michael	Choi	Michael Choi
John	Supsupin	John Supsupin
Mark	Guillen	Mark Guillen
As you need to get into the habit of making your assignment look nice, we challenge you to use either Bootstrap or Foundation. If you haven't dabbled with these frameworks, start by learning just enough to do this assignment (creating a nice looking table).

**Assignment**

1. Start a new Flask project

2. Create a route in which the data above is declared and then sent to the template engine to be rendered

3. Create the template that displays the data in a table
