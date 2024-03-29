---
layout: essay
type: essay
title: "Final Project Idea"
date: 2024-03-28
labels:
  - Software Engineering
  - Meteor
---
## ProfTCG: Professor Trading Card Game
**Authors:** Lucas Horsman, Donald Lipps, Samantha Mallari, Ethan Morrell

***

## Overview
### The Problem
Many students experience a sense of disconnection from their professors, whether it be due to large class sizes or even just a lack of personal interaction in small classes. Moreover, many are interested in learning more about their professors and have questions about what they are researching and the projects they are working on. However, it can be difficult to network and make connections with professors and ask those questions directly.

Additionally, the disconnection students experience may contribute to a lack of motivation in the class and hinder their academic performance. When students feel disconnected from their professors, they may struggle to fully engage and participate in the class or seek help when needed.

### The Solution
ProfTCG offers a fun incentive for students to engage with the class and allows them to learn more about their professors. Trading card games are very popular, and this neat twist involves the UH Manoa community and fosters a sense of belonging at the institution. It encourages students to make friends and bond with their classmates as well. During the semester, students can input courses to receive a trading card containing fun facts about their professor. Each trading card is unique to that semester and limited based on class size, thus encouraging students to collect trading cards of varying styles and rarity. Learning more about their research and projects may inspire students interested in conducting their own research and projects to come up with ideas and seek out potential mentors.

## Approach
Once a profile is created, students input the courses they are currently taking, after which the user receives their cards. On a student’s profile, it would display which cards they own. Other students can view their profile and request to trade cards.

Each card contains the following:
- Professor name
- Version (i.e, “ICS 314 Spring 2024”, “ICS 311 Fall 2023”, etc.)
- Image
- Fun Fact Description
- Rarity (for example, if there were 30 seats for a class, there are only 30 copies of that card)

Students can preview cards they don’t own, but they won’t unlock the image and description until they own it.

### Some possible mockup pages include:
- **Landing page**
- **Student home page**
- **Admin home page**
- **Student profile page:** Displays the cards the student owns and their wishlist.
- **Marketplace page:** Students are able to browse available cards up for trade and see a list of who owns the card.
- **Trade page:** View requested trades.
- **Add to Wishlist page:** Students are able to create a wishlist so students requesting trades know which cards the other person is looking for.

## Use Case Ideas
Whether or not the following bullet points list all pages or not, the completed use case should show an end-to-end scenario of using the system.

- New user goes to the landing page, logs in, gets the home page, sets up their profile, and receives their cards.
- Admin goes to the landing page, logs in, gets the home page, and is able to add cards to the site.
- User goes to the landing page, logs in, browses available cards, and requests to trade.

## Beyond the Basics
After implementing the basic functionality, here are ideas for more advanced features:
- Notifications: Students receive a notification if someone has requested to trade.
- Verification: To avoid students self reporting courses they have not taken, the app verifies with student records.
- Bonus Cards: Students can allow access to final grades, for which they can receive bonus cards for passing a class.
