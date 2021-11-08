# Party and Go

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
Don't know what party is happening this week? Feeling sad that you missed the GRAND Halloween party? **Party and Go** will solve all of your problems. The FOMO is real and we know that, we are here to make you aware of all the parties happening in the campus. **Party and Go** acts like the social media we all were missing at the campus. Let's socialize, have fun, **Party** and Goooo!

### App Evaluation
- **Category:** Entertainment/Social Media
- **Mobile:** This app is suited for mobile devices and is primarily built for mobile but it can be further stretched to an web application. 
- **Story:** The user can create an account or login to see a bunch of parties going on in campus. The user can promote their own parties. Let other people know what parties they're going to as well as search for different parties.
- **Market:** This app's market is current college and high school students.
- **Habit:** This app is meant to be engaging and fun so it will be used often.
- **Scope:** Within and Across Different Campuses

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**


* Login/Signup for User.
* Post upcoming party, using picture and description.
* Like feature for each post, visible for all.
* Comment and interact with other party goers.
* Look at other people's profile page to see what posts they have liked and what they have posted.


**Optional Nice-to-have Stories**

* Two types of users, party promoter and party goer
* Share feutre within the app
* Sort party's by popularity
* Show the nearest party from the user's location

### 2. Screen Archetypes



   * Login Screen
       * Username TextField
       * Password TextField
       * Login Button
       * Signup Button
   * Home Screen
       *    List of party posts with comments
       *    Visible Comment Section
       *    Scrollable Feed with most recent post at top
   * Search Screen
       *    Text field to search usernames.
       *    Render all users when nothing typed
       *    Clicking on the user takes to their profile 
   * Profile Screen
       * All of the posts liked and created by the user.
       

    
   * Post Screen
        * Post an image from the gallery, a potential flyer for the party.
        
  

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Login Screen
* Home Screen with bottom navigation to Post, Search and Profile Screens. 
* Post Screen with bottom navigation to Home, Search and Profile Screens.
* Profile Screen with bottom navigation to Home, Search and Profile Screens.

**Flow Navigation** (Screen to Screen)

* Login Screen
   * Home Screen
   
* Home Screen
   * Post Screen
   * Search Screen
   * Profile Screen
* Post Screen
   * Home Screen
   * Search Screen
   * Profile Screen
* Search Screen
   * Home Screen
   * Post Screen
   * Profile Screen
*  Profile Screen
   * Search Screen
   * Post Screen
   * Home Screen
   * Login Screen After pressing logout


## Wireframes
<img src="https://i.imgur.com/ARzrOOS.jpg" width=600/>

## Digital Wireframes
<img src="https://i.imgur.com/CuSFQQC.png">

## Prototype
<img src="https://i.imgur.com/8lgA7rD.gif" width=600>

## Schema 
[This section will be completed in Unit 9]
### Models
[Add table of models]
### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
