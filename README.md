# Back-End_CA2
CA2 of my back-end semester.
The new created files have been moved in the 'templates' folder, and then in the 'registration' folder.

For this defense of the project, it was necessary to keep the project which had been started in the first defense, while adding a security with a system of log-in log-out, a system of sign-in, and another to change the password in the user if this one forgot his. I used the tutorials provided by the Django website for these 3 tasks, which made this defense much easier to do than the first one, in which I had to create the application from scratch.

So I created a new template, in which the user has the choice to log in, create a new profile, or go or ask to change his password.
If he decides to log-in, he is directly redirected to the home page. In this one, I added a button to be able to log-out.
If the user decides to create an account, he is directed to a new page where he can fill in a form to create a new profile, and when he has created it, he can go back to the log-in page to connect. Otherwise, if he chooses to change his password, he is directed to a page where he must give his email address, and receive on it a link to change his password. By clicking on this link, he chooses a new password, then is redirected to the log-in page to log in.

A modification has also been made to the urls. Indeed, I used to put the user id in the url to secure my site, but now that I have created a real security, there is no need to put the user id in the url.
