---
layout: post
title: TV Listings, a React app
excerpt: This simple app queries the TV Maze API to get television show information
repo-name: tv-listings
tags: ['react', 'react router', 'react hooks', 'modular css', 'sass', 'api']
---

### Purpose
A friend was given a programming exercise by a prospective employer, and I thought it would be fun. The task was to create a page that fetched from the TV Maze API and displayed a list of search results. I then added a single show page with seasons and episodes.

### Repository
[tv-listings](https://github.com/brentdanley/tv-listings) on GitHub

### Hosting
This project is hosted on Heroku and can be found at [http://tv-listing.brentdanley.codes/](http://tv-listing.brentdanley.codes/).

### Architecture
This is a React site bailt with *create-react-app*. It uses React Router, React Hooks API, local state management, Modular Sass utilizing Grid and is responsive, Fetch API with async/await, and Helmet for injecting meta into the head.

### Functionality
The primary functionality of the site is to search for television shows. When a search term is entered into the form and submitted, the TV Maze API is queried for shows. When the JSON returns, shows are persisted to state and the view is updated. Each show poster can be clicked, after which the route and context is updated to a single show page for the relevant show. Then, the API is again fetched for seasons and episodes for the first season, and displayed. If the user clicks a season button, the API is again queried for the episodes for the selected season, and displayed.

### Git
This project uses the Git flow methodology. There are **production** and **develop** branches. New features are branched off the develop branch, and hotfixes off the production branch.
