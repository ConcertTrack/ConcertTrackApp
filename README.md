# ConcertTrackApp
App for tracking concerts attended

Original App Design Project - README
===

# inConcert (pending)

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
App for tracking one's concert attendance. 
Track bands seen, venues visited, setists from shows.

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** Recordkeeping, Social, Music
- **Mobile:** App primarily developed for mobile use
- **Story:** App helps users to keep track of concerts they have attended, as well as recording the setlists performed.
- **Market:** Fans of live music; avid concertgoers
- **Habit:** Monthy to weekly, depending on how frequently users go to concerts
- **Scope:** Initially, the app serves the user on the individual level, but as it grows, can expand to a social network of devoted concertgoers. Not broadly, but more directed to smaller focused social groups.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User can create account and log in to app
* User can add attended shows to their main record
* User can see cumulative statistics based on their attended shows
* ...

**Optional Nice-to-have Stories**

* Setlist auto-fill functionality using the setlist.fm API
* Artist reccommendations based on user's attendance stats
* shazaam-like feature that lets users listen to a song featured in a video
* User can add photos from attended shows
* User can tag other users they attended shows with.
* User can find upcoming shows from their favorite artists
* User can pick 'favorite' artists

### 2. Screen Archetypes

* Login Screen
   * User can create account and log in to app

* User Statistics
   * User can see cumulative statistics based on their attended shows
   * ...
* Main Concert/Setlist feed
    * User can view attended shows
* Concert detail screen
    * view setlist/details of attended show
* Add Concert
    * User can input date, venue, setlist
    * future features:
        * pull setlist from setlist.fm API
        * add photo
        * get spotify link to song, artist reccomendations
### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Home feed (recent shows/setlists)
* Concert statistics
* Add new concert

**Flow Navigation** (Screen to Screen)

* Login/Registration
   * Home
* Main concert/setlist feed
   * concert detail screen
   * add concert
   * user statistics
* Add Concert
   * Home (after adding new concert)
* User Statistics
   * Home
* Concert detail screen
   * Home

## Wireframes

<img src="https://user-images.githubusercontent.com/72887687/161099525-e8b6769b-1def-4965-9843-a6add5dd1021.jpg" width=600>

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype
<img src='http://g.recordit.co/4uf4uN6J3k.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

## Schema 
[This section will be completed in Unit 9]
### Models
[Add table of models]
### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
