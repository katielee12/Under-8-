# Under-8-# Under 8

Code For Good 2022
<br />

<p align="center">
  <a href="https://github.com/cfgchicago22/team-8">
    <img src="https://cdn.discordapp.com/attachments/1028018248479936633/1028279708229570660/Screen_Shot_2022-10-08_at_2.53.30_AM.png" alt="Logo" width="350" height="100">
  </a>

  <h3 align="center">Under 8</h3>

  <p align="center">
    The Under 8 App is an iOS app that provides users with a platform to learn life skills through interactive, fun lessons. 
    <br />Under 8 - Learn new skills and build a legacy, in 8 minutes or less.
    <br />
  </p>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#inspiration">Inspiration</a></li>
        <li><a href="#what-we-learned">What We Learned</a></li>
        <li><a href="#challenges">Challenges</a></li>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

Under 8 is an iOS mobile application that allows users to gain personal development skills through a series of modules posted by certified course developers. Using a format of short videos (each under 8 minutes) and quizzes, Under 8 maximizes user engagement.

<img src='https://cdn.discordapp.com/attachments/1028018248026955880/1028286742433906758/Simulator_Screen_Shot_-_iPhone_14_-_2022-10-08_at_07.40.34.png' title='Sreenshot' width='225' height='500' />

### Inspiration

Given Refined and Refreshed's goal of expanding virtual learning accessibility for low-income individuals, and the research revealing these individuals' dependence on mobile devices over personal computers, we saw a solution in leveraging the capabilities of a mobile application for their mission. We aimed to develop an app that provides users with a learning platform that does not demand an unnecessary amount of time, internet access, or technological know-how. By splitting up content in short videos and providing many opportunities for success in quizzes, and we can maximize user engagement, as well as providing easy opportunities for specialized feedback from instructors.

### What We Learned

- Technologies such as Swift, Express, Node.Js, and MongoDB
- How to connect a JS backend to a Swift application
- How to ideate and innovate as a team
- Planning out tasks efficiently is crucial to full-stack application development

### Challenges

- Connecting to the backend server to the Swift application
- Deliberating on which application features to prioritize with the team
- Picking up unfamiliar coding languages on the go

### Built With

This app was built primarily with Swift UI and we used Express.Js, MongoDB, and Node.Js on the back-end.

- [Swift](https://developer.apple.com/swift/)
- [Express](https://expressjs.com/)

<!-- GETTING STARTED -->

## Getting Started

To get started, make sure you have the latest version of NodeJS and XCode installed.

### Installation

1. Create a clone of this repository and register for a MongoDB account. Then create a MongoDB database.
2. Navigate to the API directory and run `npm install`
3. Create a .env file and paste your MongoDB connection URI.
   ```
    MONGO_URI=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
   ```
4. Start the NodeJS server using `npm start`.
5. Run the program and enjoy using the app!

<!-- USAGE EXAMPLES -->

## Usage

Figma mockups for pages in the app UI (designed by Katie Lee): [https://www.figma.com/file/YImI6e4VFZGKV4YRZmKGAS/Prototype-Frames?node-id=0%3A1](https://www.figma.com/file/YImI6e4VFZGKV4YRZmKGAS/Prototype-Frames?node-id=0%3A1)

Currently course materials can be uploaded through HTML POST and PATCH methods, such as through [Postman](https://www.postman.com/). Our backend is designed to parse HTML requests with JSON-formatted bodies.  Sample body for creating a course POST, to `host_URL/course`:
```
{
    "name": "All About Banking",
    "description": "Learn the dos and don'ts of banking!"
}
```
Sample body for adding a lesson to a course through PATCH, to `host_URL/question`:
```
{
    "courseId": //insert course id,
    "lessonId": //insert lesson id
}
```

<!-- CONTACT -->

## Contact

<b>Arpon Purkayastha</b> ([@linkedin](https://www.linkedin.com/in/arpon-purkayastha-451026197/)) - "During the hackathon, I was responsible for:
<ul>
  <li>defined the back-end infrastructure using Node, Express, and MongoDB</li>
  <li>lead in developing a REST API that the front-end can be use to manipulate user, course, class, and question data</li>
  <li>defined database schemas, constructed API routes</li>
  <li>assisted teammates in contributing to the project</li>
  <li>utilized Heroku to deploy the API in order for it to be called remotely</li>
  <li>tested API endpoints using Postman</li>
  <li>modified API endpoints to the specifications of the client"</li>
</ul>
<br /><br />

<b>Jade Zhang</b> ([@linkedin](https://www.linkedin.com/in/jade-s-zhang-833832223/)) - "I led the initial group brainstorming session, using techniques from my human-centered design class to dive into the challenge statement and ideate solutions. I also interviewed the non-profit representative to receive customer feedback on initial designs, and studied the organization's materials and website. Then I learned JavaScript, Postman, and Mango from Arpon and committed backend code (question, lesson, and course endpoint routes). After that I learned Swift online, fixed a landing page bug, and proofread this file."
<br /><br />

<b>Katie Lee</b> ([@linkedin](https://www.linkedin.com/in/katie-lee-833832223/)) - "On Friday, I took in Jade’s UX research and our whiteboard markups in order to develop the title and overall pitch of our project: Under 8 (an accessible learning platform that only take 8 minutes out of each user’s day to enrich their livelihood). I drafted up a style guide to systemize fonts, styles, and a general color scheme. After honing in on our title, I created concept art for our application logo and ran several logo iterations under a color accessibility checker to choose a final design. Next, I skimmed through sketches of example frames my team made and replicated those frames onto Figma as a user workflow. I worked with Gerdin later into the night to integrate the Figma frames into our main project. During the integration process, I finished working on our last two frames before moving onto working on the slide deck with the rest of the team."
<br /><br />

<b>Abhiram Tamvada</b> ([@linkedin](https://www.linkedin.com/in/abhiram-tamvada/)) - "I worked on the middleware models such as the UserModel that contains the information for a given user's app, developed the initial JSON Parsing Algorithm, additionally I developed the POST Request system that interacted with our database. I also worked on some front end issues such as developing a streaming video UI and fixing issues like invisible buttons, questions not being displayed correctly and questions being double clicked and changing color. Finally, I worked a lot on creating a majority of the powerpoint designs and some of the sample data for the app. I learnt a lot about git and swift both of which I have not used before."
<br /><br />

<b>Jayden McNab</b> ([@linkedin](https://www.linkedin.com/in/jayden-mcnab-3ba168202/)) - "A few of my contributions include developing the lesson page in Swift UI, which included creating the question interface from scratch, resolving several merge conflict errors with teammates, helping discuss and narrow down implementation ideas, and spearheading the creation of the final presentation powerpoint."
<br /><br />

<b>Gerdin Vertura</b> ([@linkedin](https://www.linkedin.com/in/gerdin-ventura/)) - Gerdin coded most of the frontend, including special effects, integration of screen components, course selection, and flow from screen to screen. He also brought all of Katie's figma frames to life with Swift, and taught the language to most of the team. He was too busy coding to write this statement, so we all wrote it for him. Thank you Gerdin!
<br /><br />

<b>Edgar Garcia</b> ([@linkedin](http://linkedin.com/in/edgargarcia773)) "During the Code For Good Hackathon I did the following:
<ul>
  <li>I contributed with Front End</li>
  <li>I learned Swift over night</li>
  <li>I worked on the user login page</li>
  <li>I lead brainstorming and rough sketching with Jade</li>
  <li>I worked with Full Stack Dev for outline of app pages</li>
  <li>I worked on multiple PowerPoint slides</li>
  <li>I made a team schedule for tasks and reinforced deadlines</li>
  <li>I learned about transferring APIs</li>
  <li>I used Postman for the first time!"</li>
</ul>
<br /><br />

Project Link: [https://github.com/cfgchicago22/team-8](https://github.com/cfgchicago22/team-8)
