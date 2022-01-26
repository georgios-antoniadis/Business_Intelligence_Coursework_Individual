# Business_Intelligence_Coursework_Individual
This repository includes the files necessary to build and execute the group part of the project and 
a folder including all of the necessary queries for one to create the requirements into the Metabase environment

Located also inside the repository is a video (dashboardDemo.zip) depicting the metabase tool's functionality
when it is fully configured. In this video one can also notice Metabase's limitations in the form
of long loading times for complex requirements.

How to install Metabase:
1) Download the jar Metabase file from https://www.metabase.com/docs/latest/operations-guide/running-the-metabase-jar-file.html
2) Install java on your machine (If you do not already have a version installed) https://adoptopenjdk.net/releases.html
3) Head to the directory where you downloaded the jar file and open a terminal or cmd window
4) Type "java -jar Metabase.jar"

A series of messages should appear in the terminal
If you see: ...
06-19 10:29:34 INFO metabase.task :: Initializing task CheckForNewVersions
06-19 10:29:34 INFO metabase.task :: Initializing task SendAnonymousUsageStats
06-19 10:29:34 INFO metabase.task :: Initializing task SendAbandomentEmails
06-19 10:29:34 INFO metabase.task :: Initializing task SendPulses
06-19 10:29:34 INFO metabase.task :: Initializing task SendFollowUpEmails
06-19 10:29:34 INFO metabase.task :: Initializing task TaskHistoryCleanup
06-19 10:29:34 INFO metabase.core :: Metabase Initialization COMPLETE

Then you have successfully launched Metabase.

Using metabase:
1) After having successfully installed it head to your browser and type: 
http://localhost:3000
2) You should be redirected to Metabase's home page
3) In the promp window fill in the credentials to connect with your database (Look into group repository for more information)
4) You should then be redirected to Metabase's home page
5) Head to 'Ask a question' and fill in the fields following the instructions you see inside the screenshots
of the 'query screenshots' zip folder of this repository
6) Repeat step 5 until all questions are filled in
7) Tap on the '+' icon and create a new dashboard, give it a name 'General' and click on the 'pencil' button to edit (on the top right of the screen)
8) Tap on the '+' icon to add questions and pick the questions you want from the list that will appear
9) Repeat steps 7 and 8 until you have all 6 dashboards correctly setup.
10) Head to the 'Our analytics' tab click on the clickable text and pin all the dashboards you created.
11) Head back to the home screen and you should see all of the dashboards right below the 'Hello' message on the top left of the screen
