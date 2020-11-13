# Social Network API

## Table of Contents
  - [Description](#description)
  - [Walk Through Video](#walk-through-video)
  - [Installation](#installation)
  - [Testing](#testing)
  - [Contribution](#contribution)

## Description
An API for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list.

- User Story
```
AS A social media startup
I WANT an API for my social network that uses a NoSQL database
SO THAT my website can handle large amounts of unstructured data
```

Given a social network API, when the user enters the command to invoke the application, their server is started and the Mongoose models are synced to the MongoDB database. When the user opens API GET routes in Insomnia Core for users and thoughts, the data for each of these routes is displayed in a formatted JSON. When the user tests API POST, PUT, and DELETE routes in Insomnia Core, they are able to successfully create, update, and delete users and thoughts in my database. When the user tests API POST and DELETE routes in Insomnia Core, they are able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list

## Walk Through Video
[Walkthrough](https://drive.google.com/file/d/1OaQ1tAqsZlzTTC_atDNG-M2NmvhO7DHL/view)

## Installation
`npm init`

`npm install`

## Usage
Run the following command at the root of your project.

`npm start`

## Testing
No testing is set up at this moment. Tested externally through Insomnia Core.

## Contribution
Mallory Korpics (github.com/mallynnk)