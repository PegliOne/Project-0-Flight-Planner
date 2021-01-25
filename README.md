# Project-1-Flight-Planner

A flight booking website (mimicking aviation company's online booking systems) made for the second project of the GA Software Engineering Course

---- Link will be provided here when available ---- 

## Outstanding issues

* Can't log into pre-existing accounts, since they don't have passwords
* The form to edit a flight and the button to delete a flight are on pages that show flights to non-admin users. This is risky security-wise. I'll probably have to create a separate page for admins viewing flights and use partials to put the flight info on both the admin and non-admin flight show pages 
* The site is not very user friendly and needs to provide more information (including warnings about canceling/deleting flights) to users 

## Technologies Used
* HTML (with embedded Ruby)
* CSS and Bootstrap for styling
* Ruby on Rails
* PostgreSQL 
* Google maps API (for bonus functionality)

## Sites Used For Styling
* [Coolers](https://coolors.co/palettes/popular)
* [Google fonts](https://fonts.google.com/specimen/Open+Sans?preview.text=XOXOXOX&preview.text_type=custom&sidebar.open=true&selection.family=Open+Sans:wght@400;700)

## Game Production Updates

### 25/01/21 9:40pm

Step Two Complete: Basic functionality added, including CRUD systems for users and flights, as well as the ability to search for, book and cancel flights. Users can log in, though the site currently gives no indication as to who is logged in and all of the site's functionality is available to all users. The next step is to ensure that only logged in users can access the site's functionality and that only admins can access admin-specific pages and forms.

### 24/01/21 11:50pm

Step One Complete: Database set up and seeded (users and flights appear on the website correctly). Routes, controller and views set up for users and flights. No routes, controllers or views will be needed for the airports, though they may be added as bonus functionality in Step Four. The next step is to add basic functionality (user CRUD systems, user log in / log out, flight searching / booking and flight CRUD systems).

## Game Production Plan

### Step One
* Create a new Ruby on Rails project
* Design, create and seed a database with information about users, flights, airports and how they're connected
* Design a user story and use that to set up the routes, controllors and views needed for the website
* Add the basic site layout to application.html.erb (navber, headings, etc.)
* Commit initial version to GitHub and edit readme file

### Step Two
* Add general functionality related to the users (sign up, log in, edit details, sign out)
* Add general functionality related to the flights (view booked flights, search for flights, book flights, cancel flights)
* Add admin specific functionality (view user index, create flights, edit flights, delete flights)
* Commit updated version to GitHub and edit readme file

### Step Three
* Apply permissions (make sure that users need to be logged in to use the site and that admin-specific functionality is only accessible to admins)
* Style the website using CSS and Bootstrap
* Test the website as a potential user/admin to make sure everything works
* Deploy the website (if it hasn't been deployed already)
* Commit updated version to GitHub and edit readme file

### Step Four - bonus functionality
* Prevent users from massively overbooking a flight by including data about the plane and number of seats available
* Use the Google Maps API to estimate flight distances and therefore arrival times
* Enable airports to be added, edited and deleted
* Commit updated version to GitHub and edit readme file

### Step Five
* Review and optimise code wherever possible
* Test the website as a potential user/admin to make sure everything (including bonus functionality) works
* Commit updated version to GitHub and edit readme file
