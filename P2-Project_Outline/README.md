# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time.
In particular, your mentor will provide direction and feedback to help sharpen your ideas. So don't worry if you feel
unsure about some aspects of the outline or if you have to change some things later.


### Overview
For our LiftOff project we decided to create an outdoors activity event log.
Users will be able to create and log into accounts, create, view, edit, rate, 
and delete events. Event details could include location, description, 
outdoor event type(e.g. fishing, hiking, camping, etc.), and date/time, etc).
This project could have applications for local, state, and federal parks departments,
as well as retailers, that would give users a way of sharing their experiences and providing data.
Location data, ratings, and description information could prompt park officials to potential problems
at a location. Popular locations with "good" ratings, and description data(i.e. keywords) could be beneficial 
for marketing opportunities.


### Features
User login: Users will be able to create and log into accounts. When creating accounts we want to use a ReCaptcha to
authenticate that the user is an actual person and not a "robot." To do anything other than read previously posted 
events, users will need to be logged in.
Users can create, read, edit, and delete events: Once logged in, users can create, edit, and delete events associated
with their account. Mixture required(event type, date/time) and optional fields (description, location, rating).
Users search: Users will be able to search for previously posted events based on different filters matching user input.
Filters could include: all, description, event type.
Tag location: Add location data for events and display events on GoogleMap with markers.
Rate locations: Implement a rating system(e.g. 1-5 star system) where users can rate the quality of the event they are
adding to the log.

### Technologies
Java
Spring Boot
MySQL
Hibernate
Thymeleaf templates
GoogleMaps API
Bootstrap
ReCaptcha
JavaScript

### What I'll Have to Learn
For location data we will have to learn how to make API calls to GoogleMaps. We will also need to 
learn how to use the ReCaptcha API for user authentication.


### Project Tracker
https://trello.com/b/tUy1OLVB/zac-o-group-a
