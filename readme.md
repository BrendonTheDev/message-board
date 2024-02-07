# MESSAGE BOARD APP

A mini message board app. Takes in new messages and displays them on the index/main page.

## How the app works

- The app was created using express-generator.
- I created an array to store the messages in.
- Using an ejs template I looped through the messages array to dynamically render the messages stored in messages array.
- Created a form template with the POST method on it to add the input to the messages array.
- Used req.body to access the form data and push it into messages.
  -Add a link to the new form page on the index page.

## What I learned

- I learned how to create html templates using ejs and how to dynamically render data stored in an array to those templates.
- I learned how to take data in a form and POST the data on form submit.
- I learned to push the request body from the submitted data into the storage array.
