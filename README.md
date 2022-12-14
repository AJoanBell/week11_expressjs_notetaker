# Week 11 Challenge - Expressjs Notetaker

## Your Task

The assignment is to modify starter code to create an application called Note Taker that can be used to write and save notes. This application will use an Express.js back end and will save and retrieve note data from a JSON file.

The application’s front end has already been created. It's my job to build the back end, connect the two, and then deploy the entire application to Heroku.


## User Story

```
AS A small business owner
I WANT to be able to write and save notes
SO THAT I can organize my thoughts and keep track of tasks I need to complete
```


## Acceptance Criteria

```
GIVEN a note-taking application
WHEN I open the Note Taker
THEN I am presented with a landing page with a link to a notes page
WHEN I click on the link to the notes page
THEN I am presented with a page with existing notes listed in the left-hand column, plus empty fields to enter a new note title and the note’s text in the right-hand column
WHEN I enter a new note title and the note’s text
THEN a Save icon appears in the navigation at the top of the page
WHEN I click on the Save icon
THEN the new note I have entered is saved and appears in the left-hand column with the other existing notes
WHEN I click on an existing note in the list in the left-hand column
THEN that note appears in the right-hand column
WHEN I click on the Write icon in the navigation at the top of the page
THEN I am presented with empty fields to enter a new note title and the note’s text in the right-hand column
```

## Planning

1. Clone starter code here: https://github.com/coding-boot-camp/miniature-eureka

2. Setup files

3. Create HTML routes (GET /notes should return the notes.html file.) & (GET * should return the index.html file.)

4. Create API routes (GET /api/notes should read the db.json file and return all saved notes as JSON.) and & (POST /api/notes should receive a new note to save on the request body, add it to the db.json file, and then return the new note to the client. You'll need to find a way to give each note a unique id when it's saved (look into npm packages that could do this for you).)

5. add in js to have the save button, new notes button, and clicking on the already created notes on the left hand side to be functioning.

6. BONUS -> using the uuid make it so you can also delete / remove the saved notes.

7. Deploy to Heroku

## Review

* The URL of the functional, deployed application: https://week11-expressjs-notetaker.herokuapp.com/

* The URL of the GitHub repository, with a unique name and a README describing the project: https://github.com/AJoanBell/week11_expressjs_notetaker

## Screenshots of deployed application

Notetaker landing page

<img width="1749" alt="Notetaker_landingpage" src="https://user-images.githubusercontent.com/36496885/206877813-efc33cdb-d268-46d5-896f-9a19b1aa378f.png">

Notetaker Working Page

<img width="1744" alt="Notetaker_working" src="https://user-images.githubusercontent.com/36496885/206877821-ab349b80-3054-49c3-ae87-2ff78a7c3ed1.png">


## Credits

Starter code used: https://github.com/coding-boot-camp/miniature-eureka

## Key Learnings

Server set-up
APIs
Express.js and persistent storage
The fs module
HTML Routes
Node.js
Insomnia
Heroku.
