# Overview - README 
===



# Help Me Fitness

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)

## Overview
### Description
Let users start their fitness journey easy. Users can go into the app and have videos available to them to learn proper technique for certain exercises. Users are able to formulate their own workout and save it for later. 

### App Evaluation
- **Category:** Fitness/Health
- **Mobile:** This app would be primarily developed for mobile but would perhaps be just as viable on a computer. Functionality wouldn't be limited to mobile devices, however mobile version could potentially have more features.
- **Story:** Helps fitness beginners to perform exercises through visual instruction. Users can be shown proper technique to exercises while present in the gym. 
- **Market:** Any individual could choose to use this app. For documentation purposes, the general market would be individuals above the age of 13.
- **Habit:** This app could be used as often or unoften as the user wanted depending on their fitness goals.
- **Scope:** First we would start with letting users build profiles and building their own workouts, maybe it can be expand to sharing your workouts to other profiles.

## Product Spec
### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User logs in to access workout plan/profile
* User creates/updates profile
* User searches for videos for specfic videos 
* Settings (Accesibility, Notification, General, etc.)

**Optional Nice-to-have Stories**

* Log of stats relating to workouts
* Step Tracker
* Profile Add-On: Type of User

### 2. Screen Archetypes

* Login 
* Register - User signs up or logs into their account
   * Upon Download/Reopening of the application, the user is prompted to log in to gain access to their profile information.
* Profile Screen 
   * Allows user to upload a photo and fill out information necessary for calorie count and weight adjustment. 
* Exercise Selection
   * Allows user to search for exercises. It will pull up the exercises that have vidoes and explanations. 
* Certain Exercise Page
   * This is the exercise they are looking for, but towards the whole screen. This provides the video, with tips underneath for              technique. 
* Settings Screen
   * Lets people change language, and app notification settings.

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Workout Selection
* Profile
* Settings

Optional:
* Workout Searching
* Workout Browsing (Top Workouts)

**Flow Navigation** (Screen to Screen)
* Forced Log-in -> Account creation if no log in is available
* Workout Selection (Or Browsing if Optional) -> Workout Contents Page 
* Profile -> Text field to be modified. 
* Settings -> Toggle settings
* Workout Searching (If Available) -> Text Field to be modified

## Wireframes
<img src="" width=800><br>

### [BONUS] Digital Wireframes & Mockups


### [BONUS] Interactive Prototype

<<<master

=======
<img src="https://i.imgur.com/AiKfE5g.gif" width=200>

## Schema 
### Models
#### User

   | Property      	 | Type                    | Description                                                              |
   | --------------- | ----------------------- | -------------------------------------------------------------------------|
   | profile         | Pointer to the Profile  | Profile of the User                                                      |
   | username        | String                  | unique id that is for the account                                        |
   | password        | String                  | unique id that is for the acessing the account                           |
   | savedWorkouts   | Array                   | array of the workouts that are not created by the user, saved to account |
   | createdWorkouts | Array                   | array of the workouts that are created by the user.                      |
   | goals           | Array                   | array of the goals object.                                               |


 #### Profile

   | Property      	 | Type                    | Description                                                              |
   | --------------- | ----------------------- | -------------------------------------------------------------------------|
   | image           | image                   | Image of the user.                                                       |
   | counter         | number                  | Calorie Counter calulated from infomation of the user                    |
   | gender          | String                  | The gender of the user                                                   |
   | height          | number                  | The height of the user                                                   |
   | weight          | number                  | The weight of the user                                                   |
   | age             | number                  | The age of the user                                                      |

#### Workouts

   | Property      	 | Type                    | Description |
   | --------------- | ----------------------- | -------------------------------------------------------------------------|
   | name            | String                  | unique id of the workout                                                 |
   | type            | String                  | type of workout                                                          |
   | video           | Pointer to the Video    | pointer to the video that the workout is                                 |
   | description     | String                  | discription of the video                                                 |
   | didWorkout      | Boolean                 | wheter the users has done the workout or not                             |
   | time            | Number                  | the length of time for the work out                                      |
   | intensity       | String                  | the type of the intensity of the workout                                 |

 #### Goals

   | Property      	 | Type                    | Description |
   | --------------- | ----------------------- | -------------------------------------------------------------------------|
   | name            | String                  | unique id of the goal object                                             |
   | description     | String                  | description of goal object                                               |
   | startDate       | Number                  | start date of a goal, editable of the |
   | endDate         | Number                  | array of the workouts that are not created by the user, saved to account |
>>> Zarsla
