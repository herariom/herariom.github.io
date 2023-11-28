---
author: "Logan Johnson"
title: "Ryoko"
date: "2022-12-18"
hideMeta: true
searchHidden: true
ShowBreadCrumbs: false
weight: 1
---
A website that helps users find the perfect location for their next home or apartment
<!--more-->
## Background
Ryoko is a website designed to determine the best places to live. It has a comparison tool that allows the user to input a list of homes/apartments they are looking at and the locations that regularly travel (work, school, gym, friends). For each location, they can put in the frequency and mode of travel.

Then, users can generate statistics for each home/apartment to see which one they like best based on the ease, distance, and total time traveled per week! Ryoko also has a city finder tool to search the most popular U.S. cities by preferences, including total population, population density, and distance from given coordinates.

## Technologies

Ryoko is built using the following technologies:
* [React](https://reactjs.org/)
* [Flask](https://flask.palletsprojects.com/)
* [PostgreSQL](https://www.postgresql.org/)
* [Docker](https://www.docker.com/)

APIs utilized:
* Ease of travel information provided by [Walk Score API](https://www.walkscore.com/professional/api.php).
* Distance and time traveled information provided by [Google Maps API](https://developers.google.com/maps)
* City information provided by [simplemaps](https://simplemaps.com/data/us-cities)

## Features

* Home/apartment comparison tool
* City search

## Demo

Check it out at [ryoko.herariom.com](https://ryoko.herariom.com)!

{{< css.inline >}}

<style>
.canon { background: white; width: 100%; height: auto; }
</style>

{{< /css.inline >}}
