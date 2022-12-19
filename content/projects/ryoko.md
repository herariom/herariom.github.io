---
author: "Logan Johnson"
title: "Ryoko"
date: "2022-12-18"
hideMeta: true
searchHidden: true
ShowBreadCrumbs: false
weight: 1
---
A website that helps users find the perfect city to live and work in
<!--more-->
## Background
Ryoko is a website designed to determine best places to live based on various characteristic preferences such as population, density, and distance from given coordinates.

Ryoko is a shortening of the Japanese word "ryokou," which means "travel". The name was chosen because the website is designed to help users find the best place to travel to, and because the alternative was "City Finder."

## Technologies

Ryoko is built using the following technologies:
* [React](https://reactjs.org/)
* [Flask](https://flask.palletsprojects.com/)
* [PostgreSQL](https://www.postgresql.org/)
* [Docker](https://www.docker.com/)

## Features

After filtering cities based on preferences such as total population or given coordinates, users can then click on each city to get a dashboard that allows them to view jobs, housing, and other information about the city. This includes information about the walkability, bikeability, and public transportation offered by the city. This is provided by the [Walk Score API](https://www.walkscore.com/professional/api.php).

## Demo

In the future, I plan to host a demo of the website on Heroku. Until then, you can use the website locally by cloning the Git [repository](https://github.com/herariom/ryoko) and running the command `docker compose up` in the root directory.

{{< css.inline >}}

<style>
.canon { background: white; width: 100%; height: auto; }
</style>

{{< /css.inline >}}