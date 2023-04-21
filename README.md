# CS-360-Mobile-Architect-Programming

•	Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

o	This app was created to be used as a tool to users who need a secure space to track their events with a notification feature. The requirements were the following:
	Login
   1. Create a new login.
   2. Duplicate login names are validated.
   3. Non existing username fails with a message
   4. Invalid credentials fail with a message
   5. Valid credentials login
	Database
   1. Can view all items (recycler view)
   2. Can add new item
   3. Can edit existing item
   4. Can delete existing item
   5. Cannot add item that already exists (same name, description, and date) with a message
   6. Log in as different user...perform operations for only that user (e.g. cannot see other users information)
 	Notifications
   1. No notification if setting is disabled
   2. Notification if setting is enabled
   3. Notification setting saved per user.


•	What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

  o	The screens that were necessary were the login screen, the screen that lists all saved events in recycler view, a screen that opens when the user selects an event  from the list and has the opportunity to edit or delete that event. If the user decides to edit the event, another dialog box opens, and all fields are editable. The user can also add an event from the main screen by clicking the floating button, and at that time another dialog box appears with editable fields. The last screen to implement was the screen that turned off and on the notifications. It was important to make sure that the user had a seamless experience navigating the app and changing screens effortlessly. That is what I kept in mind while developing my wireframe predevelopment of the app. Once I started working on my app, I added additional features in, like the logout button for example. Keeping the design simple yet functional is what made development of the app successful.
  
  
•	How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?

  o	The process of coding my app was a little more complex and most definitely, challenging. I started to incorporate navigation between the screens. I also developed the log in screen for the first completed functionality by adding in a hardcoded username and password to test the functionality. Once I had the menu and notifications screen up and working as well as the log out button, I started to code for the individual screens’ functionality. At the end, I linked everything up to the SQLite database and created the remaining required functionality. I believe what helped me during this part of the development stage was taking individual tasks and completing them in steps so that I was not overwhelmed or missing key components that I would have to fix later. This are the same steps I would take in the future on new apps that I am developing.
  
  
•	How did you test to ensure your code was functional? Why is this process important and what did it reveal?

  o	My process of testing was once the design was functional, I started hooking up the functionality to each of the buttons and testing to see if I got the desired outcome. This was the easiest and quickest way to test my code for the desired functionality and it allowed me to debug it to see how the code was integrating with other classes within the program. I especially did this when adding the saved events and the users to their individual tables within the database. Using DB Browser for SQLite was also beneficial in seeing the users that were already stored in the database and debugging using that information.
  
  
•	Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?

  o	The biggest challenge was most definitely the database and working out individual bugs. 
  
  
•	In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

  o	I had never even opened Android Studio prior to this class. I had zero experience in understanding or knowing how to create an app from start to finish, yet here we are 8 weeks later, and I have a fully functional app that I could launch to the Google Play Store if I wanted. So, to me it was the overall work that went into this that I feel I was most successful in completing. This is also the first time creating and implementing an SQLite database.

