java cIEMS5731 Software Design and Development (Fall 2024)
Group Course Project Specification - Web Chat Room System
Expected time: 40 hours per group
Learning outcomes:
1. To produce software as a group.
2. To experience the web service with a backend database system.
Instructions
1. Form your group, and work together for a perfect demonstration of your software
product.
2. If you use help from the AI tools, e.g. ChatGPT, or online open-source projects, e.g.
GitHub, write clearly how much you obtain help from the AI tools at the end of the group
report. No marks will be taken away for using any AI tools with a clear declaration.
3. All work should be submitted onto the blackboard before the due date.
4. You are advised to submit a compressed file (.zip/.rar) containing both your project and
group report. Only one submission is needed for a group.
5. As this is a group project, we grade the work on a group basis. If you decide to work on
your own, you will need to do all the group work.
6. The group size is at most 4 students.
7. Due dates:
a. Project demonstration: 3rd December, 2024 (Tuesday) 10:30 - 18:45 at ERB 405
b. Project and report submission: 3rd December, 2024 (Tuesday) 23:59
1
Summary of the Tasks
1. Group formation (0%)
○ The group registration starts on 12 Nov (Tuesday) at around 10 pm.
○ First, the group leader picks the time slot based on the group number (A Leader
Group X, where X is the group number).
○ Next, the group leader informs all the members to join the same member group
(The Member Group X, where X is the group number).
■ Leader should join the member group as well.
○ In case there are some issues about the grouping, the group leader can clarify or
adjust the group list by writing an email to Danny.
○ Join the groups carefully. You cannot unregister the group yourself.
○ You can form a group across the session.
○ If you do not join any groups, I will treat you as working individually. :)
■ Danny will assign the loner as the one-man band on 27 Nov (Wednesday)
night.
2. Project demonstration using localhost: (85%)
○ A login page with database connection (10%)
○ A registration page with database connection (10%)
○ Account page for updating user information with database connection (10%)
○ Multiple chat rooms selection (10%)
○ Chat room on the webpage (15%)
○ Profile picture of the user (15%)
○ Sending and playing audio in the chat room (15%)
○ Nim countdown game for all users in the same chat room (15%)
○ The score is capped by 85%.
○ The project will be demonstrated on 3rd December, 2024 (Tuesday) 10:30 - 18:45
at ERB 405
○ Do rehearse your demonstration beforehand.
○ At least one of the members presents the work.
○ For the client side, we only accept Java Server Page, JavaScript, HTML and CSS;
For the server side, we only accept Spring Boot and Spring Data. For the
database, you are advised to use MySQL.
3. Project and report submission (15%)
○ Submission of the project code (5%)
○ Group report (10%) should contain:
■ Group information
■ Text information: Features and use cases of your software
■ Images with captions: UML class diagram, database schema, UML sequence
diagram and user interfaces for the software
■ Declarations and signed receipt from the VeriGuide
■ Follow the report template
○ The project code and group report will be submitted to the Blackboard on or before
3rd December, 2024 (Tuesday) 23:59
2
Task 2.1: A login page with database connection (10%)
In this task, you are going to implement the basic login page,
● The database contains the user table.
● A user contains at least 5 fields/attributes.
● Both successful and unsuccessful login are demonstrated.
Task 2.2: A registration page with database connection (10%)
In this task, you are going to implement the basic registration page,
● The database contains the user table.
● Both successful and unsuccessful registration are demonstrated.
● For successful registration, a new entry is inserted to the user table.
● For unsuccessful registration, the user table remains unchanged.
● Data validation is performed.
Task 2.3: Account page for updating user information with database connection (10%)
In this task, you are going to design an account page for the user to update their information
after logging to the system,
● Besides the primary key (e.g. login name, or login email), users can update all the
rest of the fields/attributes.
● After submitting the information, the database is updated accordingly.
● User can navigate back to the multiple chat rooms selection page.
● Data validation is performed.
Task 2.4: Multiple chat rooms selection (10%)
In this task, you are going to design the main page of the app after login,
● The database contains the chat room information table.
● After successful login, the users will direct to this page, selecting the available chat
room or the account page.
● At least three chat rooms should be shown.
Task 2.5: Chat room on the webpage (15%)
In this task, you are going to implement the chat room,
● The database contains the message table, storing all the messages of all chat rooms
in the same table.
● When two users are in the same chat room, they can chat in real time.
● After the user joins the chat room, the user can see the history of the messages.
● Users can exit the chat room and go back to the multiple chat rooms selection page.
3
Task 2.6: Profile picture of the user (15%)
In this task, you are going to design the profile picture with the following items:
● The user table in the database stores the profile picture.
●代 写IEMS5731、Java
代做程序编程语言 If a user does not have any profile pictures, the icon showing the nickname or identity
of the user is used. You can design whether you want to save this icon into your
database or not.
● Users can upload the profile page either in the registration page or the account page.
● The profile picture (or icon) of the message sender is shown in the chat room.
Task 2.7: Sending and playing audio in the chat room (15%)
In this task, you are going to design the audio feature with the following items:
● Users can record a voice message using the microphone of the machine, and send
the voice message directly.
● Users can play the audio in the chat room.
● The audio message is also saved in the database.
Task 2.8: Nim countdown game for all users in the same chat room (15%)
In this task, you are going to design the Nim countdown game (see assignment 3) with the
following items:
● One user starts the Nim countdown game.
● The system will generate a random number between 20 and 30 at the start of the
game.
● All users in the same chat room are forced to play the game.
● The system asks the users in turn to play the game via chat message. Meanwhile,
the users can still chat as normal in the chat room.
● The game messages are stored in the message table.
● There are a lot of errors you may need to consider, for example:
○ The users give invalid numbers for the game.
○ Some users leave the chat room during the game.
○ Some users join the chat room after the game starts.
○ When encountering the above issues, some reasonable handles are
expected.
4
Task 3.1: Submission of the project code (5%)
In this task, remember to include the whole project (including all source code) in the
submission. Only the group leader uploads the work onto the Blackboard.
Task 3.2: Group report (10%)
In this task, one group needs to prepare one technical specification for your project. One
specification per group. Do follow the template of the specification.
The report will be graded based on the number of mistakes and the level of the mistakes.
We will divide the level of mistakes as “critical mistakes”, “major mistakes”, “minor
mistakes” and “small comment”. The weighting of the four types of mistakes is
1:0.5:0.3:0.1.
Task 3.2.1: Group information
In the cover page, you need to provide the following information:
● Course code and course title
● The phrase, “Technical Specification: YOUR_PROJECT_TITLE”
● Group number
● Group members information, both student ID and student name
Task 3.2.2: Features of your software
Summarize the main features (functionalities) of your software using point forms. Do not put
down many small features. Many unnecessary features are regarded as a kind of mistake.
Task 3.2.3: Use cases of your software
Describe exactly three different use cases of your software. The description of the use case
should be as specific as possible. You need to give an exact name and role for the actors.
An example of a good use case for Instagram:
As an exchange student to a new university, John uses Instagram to follow his new friends,
and also to follow the new friends’ friends through the “recommendation” service of the app.
Task 3.2.4: UML class diagram
Draw the UML class diagram to show the relations of the classes for your software. Only
show the name of the classes (including interfaces and abstract classes). No need to show
the details of the classes (fields and methods).
5
Task 3.2.5: Database schema
Show the database schema used in the (i) user table and (ii) chat room table, (iii) message
table, and (iv) any other extra tables used in your app.
Task 3.2.6: UML sequence diagram
Draw the sequence diagram for two use cases. Pick two use cases from the task 3.2.3.
Illustrate clearly the communication among different objects in the diagram.
Task 3.2.7: User interfaces
Capture all major screenshots from your product. Give a label (a, b, c, … etc) and caption
(description) for each screenshot. Besides, mark the label of the screenshot onto the flow
(arrows) of the sequence diagram.
Task 4: Declaration and VeriGuide receipt
All declarations should be made clearly at the end of the report (e.g. the extent of seeking
help from AI tools and the reference of some public GitHub or web projects). Besides, attach
the signed VeriGuide receipt of your final report. Only one member signs the receipt.
Pay attention, only the group leader submits the group report to the VeriGuide once. Never
re-submit your work to the VeriGuide. The box on the VeriGuide is called “assignment 1”
under IEMS5731. Only the group leader needs to sign the VeriGuide receipt.
Link to VeriGuide: https://veriguide1.cse.cuhk.edu.hk/portal/plagiarism_detection/login.jsp
6
Group number and presentation time matching
Do rehearse your demonstration beforehand.
At least one of the members presents the work.
Date: 3rd December, 2024 (Tuesday) 10:30 - 18:45 at
Venue: ERB 405
Group number Time slot Group number Time slot
1 10:30 - 10:45 21 15:30 - 15:45
2 10:45 - 11:00 22 15:45 - 16:00
3 11:00 - 11:15 23 16:00 - 16:15
4 11:15 - 11:30 24 16:15 - 16:30
5 11:30 - 11:45 25 16:30 - 16:45
6 11:45 - 12:00 26 16:45 - 17:00
7 12:00 - 12:15 27 17:00 - 17:15
8 12:15 - 12:30 28 17:15 - 17:30
9 12:30 - 12:45 29 17:30 - 17:45
10 12:45 - 13:00 30 17:45 - 18:00
11 13:00 - 13:15 31 18:00 - 18:15
12 13:15 - 13:30 32 18:15 - 18:30
13 13:30 - 13:45 33 18:30 - 18:45
14 13:45 - 14:00
15 14:00 - 14:15
16 14:15 - 14:30
17 14:30 - 14:45
18 14:45 - 15:00
19 15:00 - 15:15
20 15:15 - 15:30

7

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
