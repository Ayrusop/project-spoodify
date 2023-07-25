# Welcome to Spoodify

This is Spoodify. A clone of Spotify as a full-stack web app project.

## The Front-End

React and html was used on the front-end to provide a fast and seamless experience throughout the site that renders and updates dynamically. Effective modular components were also used to provide a consistent and scalable look and feel to the entire site, while not sacrificing in design or user experience. 

![Artist Page](app/assets/images/artist_page.png)

## The Back-End

The project was built on top of a Ruby on Rails back-end that communicates with a PostgreSQL database and utilizes assets that are hosted on Amazon Web Services S3. The routes and database queries were optimized to do most of the parsing of data on the database side to cut down on load times on the front-end. 

## Features

### Search

Utilizing effective back-end routes and controllers, the search page of the app can quickly and dynamically filter down the entries in the database and provide the relevant results to the user on the front-end. Filters are available to the user on the front-end in case they want to filter by artists, albums, tracks, or playlists. Top result sections are also sorted based on whether or not they contain results that are related to your search query.

![Search Page](app/assets/images/search_page.png)

### Playlist CRUD

Both a front-end and back-end authentication system was set up to give the users a more tailored and personal experience on the site. This can be seen most notable with the playlist system. Playlists can be created and played by any user, but songs can only be added and removed from a playlist by the user who created it. Additionally, playlists can only be deleted by the user who created it.

![Playlist Modal](app/assets/images/create_modal.png)

### Audio that plays while navigating the site

A core feature for any music app, the audio player is a top-level component for this app. This allows the user to stream music, change the song being played, and save the song being played to their library while navigating around the site.

![Audio Player](app/assets/images/audio_player.png)


## To run the project locally
* clone this Repository by `git clone https://github.com/Ayrusop/project-spoodify.git`.
* Now in the terminal run:
    - `npm install` 
    - `node app.js`
* Open your browser and enter url `http://localhost:3000`


## Tech Stack of this Project

* Frontend: Html, JavaScript, Bootstrap
* Backend: Nodejs, Ruby
* Framework: Expressjs
* Database: MongoDB


