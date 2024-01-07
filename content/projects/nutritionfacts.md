---
author: "Logan Johnson"
title: "Nutrition Facts"
date: "2022-12-18"
hideMeta: true
searchHidden: true
ShowBreadCrumbs: false
weight: 2
---
A nutrition facts label parsing website
<!--more-->
## Background
This application uses Tesseract OCR to analyze user-uploaded nutrition fact labels to create a searchable database of nutritional data for food products.
 
When a user uploads an image, Tesseract OCR collects relevant data from the image (calories, grams of fat, carbohydrates, and protein for a serving). Then, it stores that data in a MySQL database. Users can search for products by name that have already been added to the database to view a picture of the nutrition fact label as well as the parsed data.

## Technologies

Nutrition Facts is built using the following technologies:
* [Flask](https://flask.palletsprojects.com/)
* [MySQL](https://www.mysql.com/)
* [Tesseract OCR](https://github.com/tesseract-ocr/tesseract)
* [Docker](https://www.docker.com/)

## Demo

This site was hosted on Heroku, but unfortunately, it has broken. While I plan to fix this in the future, for now you can run the site locally by cloning the Git [repository](https://github.com/herariom/NutritionFacts) and following the instructions in the README.

{{< css.inline >}}

<style>
.canon { background: white; width: 100%; height: auto; }
</style>

{{< /css.inline >}}