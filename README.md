### List of supported endpoints
* Navigating to the /users endpoint will list all users in your app

* Navigating to the /users/:id will show the page with the information about the user with the given id

  * Returns 404 if the id was not found.
* From the browser, you can create the user

* From the browser, you can update the user

* From the browser, you can delete the user

* There is a validation error for incorrect create or update action

  * E.g. Each user has to have an email and an error is displayed if this required value is not provided
* Users index page (/users) shows the list of all the users; for each user, it shows the list of all posts that belong to the given user, and for each post, it shows all the comments that belong to the post.
