# SpamPrevention
Two different methods for dealing with incoming spam in regards to contact
forms.

## Description
Method 1: [Formspree](https://formspree.io/) is a service used for sending emails from a static HTML page 
without having a supported backend.

    > _gotcha (Formspree feature): "Honeypot" used to catch spam by fooling scrapers.
    
The Formspree Github Repo can be found here: [Formspree Github](https://github.com/formspree/formspree)

Method 2: [Mailto](http://www.rapidtables.com/web/html/mailto.htm) is a URI scheme indicating that a certain text is an email address.
An email client must be installed on the machine for this to work.
Encryption techniques using a mixture of JavaScript and HTML are used in an attempt to fool spam bots.

## Prerequisites
Most browsers support JavaScript, but the latest version of
[Chrome](https://www.google.com/chrome/browser/desktop/index.html) is highly
recommended.

# Usage
The email addresses used are sample emails. The emails need to be manually
changed for the purpose of self-testing.

    > john.doe@gmail.com --> [yourEmail@email.com]

# Disclamer
Note: These methods are only an attempt to fool bots that are not guaranteed to be 100% spam-proof. 

