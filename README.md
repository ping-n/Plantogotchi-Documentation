# Plantogotchi

## Table of Contents:

---

| #   | Content                                                               |
| --- | --------------------------------------------------------------------- |
| 1   | [Purpose](#purpose)                                                   |
| 2   | [Functionality / features](#functionality--features)                  |
| 3   | [Target Audience](#target-audience)                                   |
| 4   | [Tech Stack](#tech-stack)                                             |
| 5   | [Dataflow Diagram](#dataflow-diagram)                                 |
| 6   | [Application Architecture Diagram](#application-architecture-diagram) |
| 7   | [User Stories](#user-stories)                                         |
| 8   | [Wireframe](#wire-frames)                                              |
| 9   | [Task Management](#task-management)                                   |


## Purpose

---

The purpose of this web application is mainly designed for leisure, it was created for anyone who enjoys gardening but lacks the space or time to take care of real plants. The main objective of this application is to allow users to take care of a virtual plant in a Tamagotchi style environment. The users will able to grow a range of different plants for the sake of entertainment or to improve mental health during these difficult times.

#### Current Problem

The current COVID-19 global pandemic has had a significant impact on our society as people are being forced into lock-down restrictions that see them losing their jobs or unable to see their friends or loved one, all of which have a huge negative impact on their mental health. An [article](https://www.sahealth.sa.gov.au/wps/wcm/connect/f584ac43-db54-44d5-a5df-82c6415f18d7/20200501+Mental+Health+and+COVID-19+Fact+Sheet+-+Information+for+the+com....pdf?MOD=AJPERES&amp;CACHEID=ROOTWORKSPACE-f584ac43-db54-44d5-a5df-82c6415f18d7-n7t8sdk) from the South Australian government has detailed a list of impacts on the mental well-being of people during this difficult time. 

Plantogotchi was created as a simple web application that allow users escape from the stress they may face during the COVID-19 pandemic by providing them with something easily accessible, with their only barrier to the applictation being internet access and possession of a computer device. Studies have shown the [benefits](https://www.thesill.com/blogs/care-miscellaneous/why-you-need-plants-in-your-life) of having indoor plants. Although Plantogotchi is virtual plant game, we aim to provide our users with similar benefits.

Source:
- https://www.thesill.com/blogs/care-miscellaneous/why-you-need-plants-in-your-life
- https://www.sahealth.sa.gov.au/wps/wcm/connect/public+content/sa+health+internet/conditions/infectious+diseases/covid+2019/coronavirus+disease+2019+covid-19

## Functionality / features

---

* Ability to plant a seed/create a new plant.
* Ability to monitor the plant's health.
* Ability to water (or fertilise) the plant if necessary.
* Plant grows over time if health is maintained.
* Plants dies if left without maintenance.
* For every plant that reaches the final stage of growth, the user is allowed to create one more plant.
* User profile displays user's name, bio and plants.
* User account page where details can be changed, password reset.

#### Future feature

* A shop within the application that allow to user to purchase rare plants, fertiliser or other boosts to gameplay such as an automatic watering can.
* Level system which allow user progression, for example; to unlock new plants or abilities.
* Allow users to collect badges/achievement from progressing through the web application.
* A page for the user to show off their collection to other users.
* Comments or chat functionality to allow the user to connect with other users.

## Target audience 

---

Plantogotchi to designed for any person interested in gardening, particularly those who lack the resources to garden non-virtually. As outlined in our user stories, the application may be particularly useful to those looking for some form of virtual companionship, or those wanting to experience giving care. Plantogotchi would be a great application for children as it may teach them the responsibilities that come from taking care of another life form. It would make a great introduction application for children whose parents wish to find out if the child is responsible enough to own a real plant or a real pet. Other than children, Plantogotchi will also appeal to adults who love gardening but lack the time or resources to invest in a real plant. 

User will have the ability to grow different type of plants. As their profile levels up, more varieties of plants will be unlocked which enable a sense of progression within the application. Plantogotchi's simple gameplay means that the elderly can easily pick up the application and play on their phone, giving them the ability to play with their grandchildren over the internet, especially within this global pandemic which prevents them from interacting with their grandchildren in real life due to the elderly being more susceptible to catching the virus. Applications like Plantogotchi may be helpful for them to connect with family members and hopefully alleviate some of the stress that they have accrued over such a difficult time.

As Plantogotchi expands, we hope to add features such in-game chat or a comments system to allow people to connect or play with their friends and families. This feature will be our main focus straight after we launch the first playable version of Plantogotchi as we feel that these features will be great for the community to have as another avenue to make friends in such stressful time. 

## Tech stack

---

Back-end Framework

- Ruby on Rails

Front-end Framework

- React

Database

- PostgreSQL

Version Control

- Git & Github

Deployment Services

- Heroku
- Netlify

Project Management Tools

- Trello
- Discord



| #    | Component                                                    |
| ---- | ------------------------------------------------------------ |
| 1    | Ruby on Rails: Back-end of the web application, enable the web application to have a persistence of data. |
| 2    | HTML5 & CSS: To output the application content in the browser while providing the ability to style pages of the web application. |
| 3    | React.js: A JavaScript framework that allows the creation of quick and powerful client-side web applications. |
| 4    | Node.js: A JavaScript runtime environment which allows JavaScript code to run outside the web browser, such as on a server. |
| 5    | Heroku: A deployment platform for the web application which hosts our back-end (Rails API) and persistent database. |
| 6    | Netlify: A deployment platform to host the front end of web application (React). |
| 7    | PostgreSQL: A relational database management system to hold all of the persistent data from the web application. |
| 8    | Git: Version control to backup source code of the application in local environment. |
| 9    | Github: Web repository hosting service, which allow members within the team to collaborate on the project as well as providing a remote backup of source code. |
| 10   | Trello: A web application that allow team members to manage the project by creating and assigning tasks. |
| 11   | Discord: An application for instant messaging and VoIP service. We use discord to communicate ideas and hold daily stand ups. |

### Front-end Library

---

| #    | Library                                                    |
| ---- | ------------------------------------------------------------ |
| 1    | Axios: Promised based HTTP client for the browser and node.js which allow us to make HTTP request to our rails api  |
| 2    | Semantic-ui-React: Component based semantic ui integration with React, allow us to follow add semantic styling to our project by using semantic ui component. |
| 3    | Semantic-ui-css: Allow us to import the css styling from semantic ui, we are using a less version which give us more control over semantic ui default styling. |
| 4    | Node Sass: Node-sass is library that bind Node.js to Libsass, which allow us to write scss in this project as it automatically compile scss into css. |
| 5    | React-router-dom:  |


### Back-end Library

---



## Dataflow Diagram

---

<img src="./docs/data-flow-diagram.png" width="80%">

## Application Architecture Diagram

---

<img src="./docs/Arch-Diagram.png" width="80%">

## User Stories

---

### **Barbara**

Barbara lives a solitary existence, trapped in a small, damp and mold-ridden room of the West Maribyrnong "Keep 'Em Till They Kark It" retirement village. She spends most of her days sitting in her worn floral armchair peering out into the village's pitiful garden, reminiscing of her youth spent elbow deep in the soil of her father's potato farm. Years pass like this until one day, during one of her annual visitations, her grandson shows her a web application on his phone; Plantogotchi. 

At first, she does not quite make out the strange green hue emitting from the grandson's mobile telephone, but upon fitting her 26x prescription glasses she finally makes out a small flower sitting in a pot. At once, her years of depression fade away and she is overcome with joyous ecstasy. A blinding white light breaks through the dark clouds above and shoots down onto the phone. She knows at once what she must do, and grabs the phone from her grandson's hand. "GET OUT OF HERE!" she screams at him as he cowers in the corner, before he runs out the door. 

She relaxes back into her floral armchair and notices the plant looks a little brown and withered, and thinks to herself "my baby needs some water", content with her new-found friend.

### **Richard**

Richard is a busy man. After recently taking a promotion at Phillip Morris International, he has been completely inundated with work surrounding the several million lawsuits the company is facing for misrepresenting the dangers of tobacco use. No matter, Richard keeps on top of things by disregarding all other facets of life and by consuming 750mg of caffeine daily. Richard is a workaholic.

Recently, Richard has been having strange, unnatural feelings; The need to care for something. At first he considered buying a pet, but that would ruin his pristine penthouse apartment and require going to a grocery store, which he **hates** doing. He considered growing a plant, before he realised that would likely involve having soil in house, a common host for mycotoxin-emitting micro-organisms, that would not do.

One day, while scrolling through his Golf Club's Facebook feed, he notices a well-composed marketing campaign for a web application; Plantagotchi. "This app is free?! Rookies!". He downloads the app on-the-spot and starts growing a small cactus. He likes looking at it so much, that he buys an extra LCD monitor just so he can watch his plant grow while he works.

#### Barbara and Richard's Stories

- As a user, I want a simple/intuitive user interface, so that I can start caring for my plant immediately without the need for training.
- As a user, I want multiple breeds of plant to choose from, so that the game remains interesting for me over time.
- As a user, I want to have an account, so that I can keep my progress and change my details.
- As a user, I want to have a profile, so that I share my plants with friends.
- As a user, I want to have to have third-party authorization, so I can make an account quickly without a new password to remember.

---

### **Ping**

Ping is the admin (and creator) of Plantagotchi. He cares about his users, and wants to make sure his applications runs smoothly. While he has done extensive testing before releasing the app, you can never be too careful and thus he creates admin functionality to maintain the software and resolve any issues or bugs that may arise.

#### Ping's stories

- As an admin, I want to have full rights to create, update, delete or destroy plants, so that I can test and maintain the database.
- As an admin, I should have the ability to moderate user progress and help users with any queries they may have.
- As an admin, I want to have the ability to reset user's passwords, so that I can assist users who lock themselves out.
- As an admin, I want the ability to control the speed of the game, so that I can easily debug it without waiting for hours.

## Design

---
The initial inspiration of Plantogotchi come from the old-school Tamagotchi handheld device that we owned growing up, which taught us to be responsible by feeding and taking care of a virtual pet. We had a lot of fun playing with Tamagotchi as children so we wanted to re-create that theme but incorporate our hobbies as adults. The theme of Plantogotchi is to create a retro aesthetic application by incorporating pixel font and utilising pixel art to represent our plants. The main functionality of our web application is caring for and growing plants, therefore we wanted to make sure these features are included in our MVP while keeping other features relatively simple and straight forward.


The Mood board below represent our initial thought process when choosing the design of our application:

<img src="./docs/Design/moodboard.png" width="80%">

It mainly includes inspiration we found regarding Tamagotchi and pixel art from games that can use as inspiration in our application.

#### Font

We wanted the font to represent the style of a pixel-art game so we found a range of pixel fonts that best represent the theme we are trying to achieve.

Digital Disco font is the font that we decided to go for in the mock up which is why it is used in the wire frames. We believe that the Digital Disco font is really easy to read and the clean pixel design perfectly matches what we want for the web application in terms of accessibility and aesthetic. 

<img src="./docs/Font/disco-font.png" width="80%">

The LL Pixel font leans heavily toward pixelation. We liked the initial look but felt it may shift the attention of users away from the game play of the web application.

<img src="./docs/Font/LLPixel.png" width="80%">

Pixel Bug font really stands out, it is unique and fun to look it. The main problem we had with Pixel Bug is that it can be difficult to read on mobile devices and may shift the focus of users away from the other functionality of the application.

<img src="./docs/Font/pixel_bug.png" width="80%">

Source:
- Digital Disco: https://www.dafont.com/digital-disco.font
- Pixel Bug: https://www.dafont.com/pixel-bug.font
- LL Pixel: https://www.dafont.com/llpixel.font

#### Colour

The colour palette below was generated by inverting the three most dominant colours within the sprites of our plants. A main objective of Plantogotchi is allow user to customise the colour of their user interface to create a web application that can reflect their personality. Hopefully this makes users more invested in our application. The final goal of our application is to allow our user to choose their own background however the freedom of user choice can create different problems. Giving user the choice to choose colour combinations may result in the UI being harder to read because they might choose an unsuitable colour combination that lacks contrast resulting in other features of the application being highly unreadable. To counter such a problem, we came up with the solution of limiting the colour choices by offering only inverted colour to the user, this means any colour the user can choose will not have a negative effect of the readability of the plant itself (the core feature of the application).

These colours are the inverted colours of our three starter plant sprites, ultimately we want to create an application with a fun and soothing environment for the user.

<img src="./docs/Color/colour1.png" width="80%">

<img src="./docs/Color/colour2.png" width="80%">

### Site Map

Below is a basic site map of the application:

<img src="./docs/Design/site-map.png" width="80%">

### ERD

The ERD represents the relational relationship of different model tables within the database. Plantogotchi is a relatively simple web application therefore we wanted to design the database in a simple way to represent all aspects of the application.

User:
- The user model will hold all information regarding the user such as username, email and password.

Plant:
- The Plant model will hold data regarding the plants and it is therefore crucial to the main functionality of the application.
- The 'water_level' and 'food_level' attributes will represent the growth logic of the plant, if the water and food level is sufficient then the plant will grow to the next stage.
- The 'alive' boolean attribute allows the application to quickly check whether the plant is alive without doing calculations with other attributes. If the plant is dead then information will need to be conveyed to user through the front-end framework, and functionality of that particular plant will be disabled.
- The 'growth_stage' attribute is an integer to represent the growth stage for a particular plant type in comparison to the 'max_growth' of that plant's breed. This comparison allows us decide which sprite to render for the plant, which will represent the plant's growth visually to the user.

Breed:
- This will hold all information regarding the different type of plants available.
- Being in separate tables allow us to scale the application in the future by add more breeds or plant types.
- The max_growth field is integer representing the total stages of growth for that plant, which is dependant on the number of growth sprites available for a given breed.

Event:

* This table will hold all the events, or user interactions that may impact the plant's growth.

* The 'type' attribute' is represented as an enum to allow us to expand the database in the future. Using enum attributes is flexible and allows us to use less data space to identify what type of user interaction has occurred.

Below is the ERD of the application:

<img src="./docs/Design/ERD.png" width="80%">

#### Model Relationship

- User and Plant
  - A User has many Plants.
  - A Plant belongs to one User.
- Plant and Breed
  - A Breed has many Plants.
  - A Plant belongs to One Breed.
- Plant and Event
  - A Plant has many Events.
  - An Event belongs to One Plant.

## Wire-frames

---

The wire-frames below are a direct draft of the web application's visual layout. The colours represented in the wire-frame do not reflect the final product as we hope to give our user the ability to customise the colours of the background and UI to make the application feel unique for individual user. The wire-frames were designed in Figma, each wire-frame includes three different dimension to represent user accessing the application from a range of different devices.

Size:
Desktop: 1440x1024
Tablet: 834x1194 (iPad Pro 11 inch)
Mobile: 360x640 (Average Android phone size)

#### Landing Page

The landing page will include an animation showing game-play, giving new users a peek at the overall functionality of the web application. There will also be user reviews to attract potential users to sign up and try out our application.

<img src="./docs/wireframe/landing-page.png" width="80%">

#### Main App Page

This is the main feature of the application which is where the user will interact with their plants. We wanted to design the layout in a way where the plant is the first thing the user sees when they log on. This is why we position the plant directly in the centre of the application, to make sure that the most important data is conveyed to the user quickly, such as the water and growth level bar. In order to make the application fun and enjoyable, our main goal is allow users to interact with the plant quickly and to see all information they need to effectively take care of their plant. 

<img src="./docs/wireframe/Main-App.png" width="80%">

#### Login/Sign up Page

This is where the authentication process take place, we want to keep these two pages simple and straight forward. This pages will allow users to quickly login or sign up, then get straight into the gameplay loop of the web application. We want to give users the ability to authenticate through their other social accounts such as Google or Facebook in order to shorten the registration process. The presence of Google and Facebook sign-in options will also create a good impression on potential users by giving them the ability to login or sign up with a platform that they already trust.   

<img src="./docs/wireframe/Login.png" width="80%">

<img src="./docs/wireframe/Sign-up.png" width="80%">

#### About Us

A really simple and straight forward page to give the user a brief introduction about the application. The main objective of this page is to entice new users to sign up once they have finished with this section.

<img src="./docs/wireframe/about-us.png" width="80%">

#### FAQ

A simple page created to provide users with basic answers to frequently asked questions as well as a contact form which they can fill out to reach the admins/creators of the application. The contact form will make use of the Formspree SaaS, in order to avoid having to store messages in our persistent database. 

<img src="./docs/wireframe/FAQ.png" width="80%">

### Wire-frame Demo

Below is a demo for the wire-frame, clicking on this [**link**](https://www.figma.com/proto/bPJuz1UPRUSFjCFz4lDSTF/CODER-FINALPROJECT-A?node-id=0%3A3&scaling=min-zoom) will allow you to go through the wire-frame in real time.

<img src="./docs/wireframe/wireframe-demo.gif" width="80%">

### Wire-frame Relationship

<img src="./docs/wireframe/relationship.png" width="60%">

Please visit this [**link**](https://www.figma.com/file/bPJuz1UPRUSFjCFz4lDSTF/CODER-FINALPROJECT-A?node-id=0%3A1) to view the wire-frames. Navigate to the prototype tab in Figma will highlight the relationship between each pages in greater detail.

## Task Management

---

This project utilises Trello as a project management tool which allows us to allocate tasks to individual members of the team. We also utilise Discord as a platform to collaborate on this project, allowing us to hold meetings and communicate with each other to effectively resolve issues and allocate new tasks to be completed. During the project we will implement Agile development principles to develop our application by creating an effective road-map and working on the project in a modular process by dividing tasks to into smaller achievable tasks.


We have provided screenshots below to illustrate the progress of the project each day. As a team we have a daily stand-up in which we go through what we have done the previous day and what we plan to do that day. We also allocate each card/task to a specific member to complete each day. Within the Trello board we utilise the built-in features such as colour labels and checklist to effectively plan and delegate tasks through the member assigning system. 


Below is the Trello board progress for Part A of the project:

Trello Link:

https://trello.com/b/DdUvzfZU/final-project-part-a-coder

Day One:

On Day One we mainly focused on gathering inspiration and delegating the first set of tasks to individual team members according to their strengths and weaknesses. Day one is relatively empty because we spent a huge amount of our time having a meeting to plan out the features of the application, in accordance to the criteria for the project. 

<img src="./docs/Trello/DAY-1.png" width="80%">

Day Two:

Day Two represents the starting point of the project, we had a quick meeting in the morning to discuss and delegate the tasks for the day. During the meeting we created the ERD as a team (via pair programming) so we both understand the information we need to store for the application. We also spent the entire day planning and setting up the overall objectives to effectively meet the deadline of the project.

<img src="./docs/Trello/DAY-2.png" width="80%">

Day Three:

Day Three involves starting and finishing off the design elements of the application such as wire-frames, user stories and discussing about the features we need to create in order to meet our MVP for the application. Today we also studied the criteria in more details to ensure we are meeting the requirements for Distinction to High Distinction for the assessment.

<img src="./docs/Trello/DAY-3.png" width="80%">

Day Four:

Day Four was the designated final day we allocated for Part A of the project as we wanted to prioritise development time to work on Part B. Day four mainly involve proofreading the Readme and adding all relevant details to ensure we met the set criteria of the assessment. We also included attachments within the Trello cards to showcase the tasks we have completed as well as to gather input in regards to what else we needed to include in our documentation. 

<img src="./docs/Trello/DAY-4.png" width="80%">