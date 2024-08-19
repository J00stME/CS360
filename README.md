# CS360 Final Project- Reflection

This application required an account creation / login activity as well as a database management and visualization tool.  This required a login screen, create account screen, database screen, and create item screen as reflected in the 4 layouts and activity classes.  The database screen made use of edit and delete widgets as well as a popup text box for changing item quantity.  There is an SMS feature that makes use of system permission requests but so far I have not been able to emulate real SMS messaging.

My approach to testing was a little haphazard, changing one thing and refreshing the app repeatedly.  I probably would have done good to test deeach indiviudal activity one by one but in my experience this was not entirely necessary... I got it done despite all this.

There are many different ways to develop UI in Android and I chose the most lightweight option I could find or understand... activities, intents, and a custom ListView.  The only state I needed to manage were the databases.  In the future I may bundle state info with individual accounts but I believe that was beyond the scope of this project.

I was most proud of the database view with dynamic objects and interactive widgets on the DatabaseActivity... this was the most fun and satisfying part for me.
