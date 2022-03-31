<!-- Original App Design Project
=== -->

# ClassPass

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes) 
2. [Schema](#Schema)

## Overview
### Description
ClassPass is an app for students to easily join a space where they can collaborate, chat, and get to know fellow classmates easily with just their course number. 

### App Evaluation
- **Category:** Productivity/Education and Social App
- **Mobile:** Mobile first experience.
- **Story:** Allows users to to interact with other users in the same class.
- **Market:** Any student in university. 
- **Habit:** Users can chat throughout the day many times. Features like file and photo upload allows users to share content to each other. 
- **Scope:** Mainly our focus is for UC Merced as an MVP. But potential scope can be expanded to any public university. 

## Product Spec 

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User can login 
* User can create a new account
* User can upload photos
* User can upload files
* User can chat with other users
* Users can join class chatrooms with a specific classroom ID
* User is notified of activity in the chatroom

**Optional Nice-to-have Stories**

* Users can mention other users specifically
* Users can like a message
* Users can react to a message
* Users can privately message other users
* Users can pin a message
* Users can transition to light and dark mode

### 2. Screen Archetypes

* Login Screen
    * User can login with email and password
* Registration Screen
    * User can register with name, email, and password
* Dashboard
    * User can see all their chatrooms that they are registered in
* Chatroom
    * User can chat with other users
    * User can upload photos
    * User can upload files
* Settings
    * User can change their profile picture
    * User can change their handlename
    * User can change their password
    * User can mute or enable notifications


### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Home Feed - Where all the class chats that you are part of are located.
* User/Settings Tab - User can edit the settings for their account along with the settings of the app.
<!-- * [fill out your third tab]
 -->
**Flow Navigation** (Screen to Screen)

* Classes Screen
   * Consists of all the class chats the user has enrolled themseleves in. 
   * Plus button on top right corner for user to add additional classes.
* Class Chat Screen
   * User sees the messages and content sent by other users in the class chat.
   * User can send messages or upload images and gifs.

## Wireframes
<img src="https://github.com/akheel-s/ClassChat-Project/blob/main/wireframes.png" width=600>

<!-- ### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype -->

## Schema 
### Models

| Property     | Type      | Description     |
| ------------- | ------------- | -------- |
| courseId          | Long         | CRN (UC Merced specific) Course Code  |
| name           | String         | Name of user  |
| email           | String         |  Email of user |
| password           | String         | Password for user |
| message           | String         | Messagess on chatroom |
| courseName           | String         | Name of the course |


### Networking
- Read/GET Get the login information(username(email) password)
- Create/POST Create a new message in chatroom
- Create/POST New user registration
- Create/POST User adds themselves to a class chatroom
- Delete Leave chatroom for course


