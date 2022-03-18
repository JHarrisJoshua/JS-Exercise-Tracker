# Exercise Tracker - Full-Stack MERN App

## Table of Contents

1. [Video Demo](#Video-Demo)
2. [Overview](#Overview)
3. [Program Spec](#Program-Spec)

## Video Demo
### Extended Video (higher resolution)
<https://youtu.be/G8hgM80De7Q>

### GIF (lower resolution)
![exercise_trackerGIF](https://user-images.githubusercontent.com/81477294/158917890-a1661ec0-9a30-4942-9a31-50a453effa64.gif)

## Overview
### Description
The program represents a web application that tracks exercises performed during a workout. The REST API for the app is implemented using Node, Express and MongoDB. The UI is implemented separately using React to complete the full-stack MERN app. 

## Program Spec

### 1. User Stories

**User Stories**
* User can view their exercise log when the page is rendered. The home page displays all of the exercises stored in a MongoDB collection.
* Each exercise can be edited or deleted by clicking the respective icons.
* Clicking the icon for editing brings the user to the edit page. Information for the selected exercise is populated and can be updated and saved to the database. Upon saving, the user is directed back to the home page. 
* The user can switch to the Add page in order to add exercises to their log.

### 2. Application Details

**App Files**
* 'tracker_react/' - subdirectory containing the files for the UI implemented with React.
1. Model
2. Controller
* 'tracker_rest/' - subdirectory containing the files for the REST API implemented with Node, Express, and MongoDB.
** 
