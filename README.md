Learning Goals
--------------
This simple homework will teach you the basics of web development, you'll learn about how to send HTTP requests to your program and how to respond to them in various settings.
After completing this assignment, you will know how to:

* Send HTTP requests.
* Respond to HTTP requests.
* Create and interact with forms.
* Write Embedded Ruby code in an HTML page.
* Write in-line styling.

Instructions
-------------
Create a page that displays "Hello $USER" where $USER is the name provided by the user in a form.

1. Clone this application in codio or your machine.
2. Fix the form so it sends a POST request to /hello.
3. Fix the hello.erb file so it outputs the name obtained from the form as "Hello $USER".
4. Embed a Ruby for loop to repeat the message 5 times.
5. Modify the style of the message, with in-line styling, to change the color of the text to blue.

Example Solution 
![image](https://user-images.githubusercontent.com/7307397/190445805-35795fe9-3ac1-45df-b45a-9a9295c80ff7.png)


Testing the program
-------------
Every time you start a new Ruby program make sure to run ```bundle install``` it will download all dependencies necessary for the program.
Run your app by executing the following command ```bundle exec rackup --host  0.0.0.0```
Once the app is running, open the app using the Codio "Box URL" button, a new tab should open with a URL like this ```https://floodrose-energycantina-3000.codio.io/``` change the 3000 for 9292 in the URL and press enter, you should get a new page with an error. That is because the program is only listening to the routes we specified in app.rb, add ```/hello``` at the end of the URL and it should take you to the hello_form.erb file.

Submission
------------
1. Clone this repo on codio or on your computer and complete the required functions and pages.
2. Commit and push your solution to GitHub (make sure you pass all the tests before you do), double check your repo on GitHub and verify the commit went through.
3. Submit in Blackboard a picture of the program displaying "Hello $USER" 5 times in the web page.
