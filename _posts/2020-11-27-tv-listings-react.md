---
layout: post
title: TV Listings, a React app
excerpt: This simple app queries the TV Maze API to get television show information
repo-name: tv-listings
tags: ['react', 'react router', 'react hooks', 'modular css', 'sass', 'api']
---

### Purpose
Mostly built this for fun, but I thought it would be interesting and challenging. It gave me the opportunity to learn about the React Hooks API, which I used throughout for state management, instead of component classes.

### Repository
[bowling-scores](https://github.com/brentdanley/bowling-scores)

### Hosting
 This project is hosted on Heroku at [http://bowling-scores.brentdanley.codes/](http://bowling-scores.brentdanley.codes/)

### Architecture
This is a React site, built with **create-react-app**. The primary components are the bowling roll buttons for input, and the frames for output. The rolls component updates state at the app-level, which triggers an update of the frames view component. 

### Functionality
The user clicks buttons corresponding to the number of pins knocked down on a roll of the bowling ball. If not all pins are knocked down on a roll, only the pins still standing are available to be knocked down on the subsequent roll, just like in real bowling. The frame display is updated on each roll, as are the frame and string scores. 

For various scenarios, a dialog educates the user regarding how the scores is calculated.

### Git
Uses the Gitflow methodology. Branches are *production* and *develop*, with *feature* branches off develop and *hotfix* branches off production (to be merged back into both/all).