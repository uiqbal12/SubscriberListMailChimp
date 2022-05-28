# SubscriberListMailChimp
Subscriber list using Mail Chimp servers using HTTPS api


This is a full-stack application using Express.js, node.js, JavaScript and HTTPS api methods. 

The application presents a front-end signup page where the user can punch in their details namely First Name, Last Name and email. 

Upon hitting the submit button, the application will connect with the MailChimp Servers apis and if the authorization built within the application 
is passed, a success Jumbotron will be displayed. In the case of a failure, a failure Jumbotron page will be displayed with a Try again button. This try again button
has a "/failure" route configured for the user to try again. 
