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
This site allows users to upload images of the nutrition fact labels on products along with the product's name. It then utilizes Tesseract OCR to collect relevant data from the image such as the calories, fat, carbohydrates, and protein for a serving. Then, it stores the data in a MySQL database. Users can search for products that others have submitted and see the nutrition facts of that product.

## Technologies

Nutrition Facts is built using the following technologies:
* [Flask](https://flask.palletsprojects.com/)
* [MySQL](https://www.mysql.com/)
* [Tesseract OCR](https://github.com/tesseract-ocr/tesseract)
* [AWS](https://aws.amazon.com/)

## Features

After filtering cities based on preferences such as total population or given coordinates, users can then click on each city to get a dashboard that allows them to view jobs, housing, and other information about the city. This includes information about the walkability, bikeability, and public transportation offered by the city. This is provided by the [Walk Score API](https://www.walkscore.com/professional/api.php).

## Demo

This site was hosted on Heroku, but unfortuantely it has broken. I plan to fix this in the future, but for now you can run the site locally by cloning the Git [repository](https://github.com/herariom/NutritionFacts) and following the instructions in the README.

{{< css.inline >}}

<style>
.canon { background: white; width: 100%; height: auto; }
</style>

{{< /css.inline >}}