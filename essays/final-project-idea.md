---
layout: essay
type: essay
title: "Final Project Idea"
date: 2025-11-04
labels:
  - Software Engineering
  - Nextjs
---

## Overview

### Problem

- Students often don't have their own cars
- Students don't know other people with cars
- Uber and Taxis are expensive
- Public transit can be time consuming and unreliable

### Solution
**UH Rideshare** — a web application tailored to UH students that helps:
- Find students with a car who are willing to drive
- Communicate with others about commute times and destinations
- Post about active events to search for others who are going
- Request gas money for driving

---

## Approach

Build on a Next.js (ICS 314 starter) web app and add communication/rideshare features:
- Secure login via .edu email
- Instant messaging feature
- Storing vehicle details and habits in a database
- Route sharing and safety parameters
- Hosting profiles to match drivers/riders

---

## Use Cases

### Student requesting a ride
1. User logs in
2. User finds active rides, if any. If not, send an announcement to drivers with time and destination. 
3. Find driver, meet with driver. 
4. Driver arrives at destination, user gives payment and optional rating

### Student offering to drive somewhere
1. Login to the application via UH email.
2. Navigate to 'Create a Ride' page.
3. Create the ride, specify event time/departure, maximum passenger count, price per ride, category.
4. Wait for response/notification of a user who is looking for that ride in the chat page.
5. Communication for meetup in an instant messaging tab.

### User hosting an event
1. Login to the application via UH email.
2. Navigate to 'Create a Event' page.
3. Create the event, specify time/location, maximum attendance count, category.

### Admin intending to edit page
1. User logs in with admin credentials.
2. Visits the page they intend to edit (which displays additonal information due to role).
3. Documents the changes that need to be made, can fill out a request form for developers.

---

## 

- **Home:** homepage with navigation options to all other webpages on the site.
- **Profile:** page where you can upload and update information about yourself.
- **Active Events:** allows students to search for active events using a map of Oahu.
- **Request a Ride:** place that users can use to post and request a ride somewhere.

---

## 

Potential features to extend the app:
-  Starred rating system for events/drivers
-  Payment in-app using secure transfers
-  Additional social-media aspects that allow posts from previous events
-  Link to cheapest uber in case there isn't available rides.
-  Map of bus routes for fallback.
-  Event sorting and filtering.
-  Feedback form that links to developers.

---

## Team & Notes

- This idea was written by Christian Komo, Denny Huang, Thomas Chen, and Peter Law as a brainstorming essay.  
- **Author:** Peter Law
