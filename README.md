# Portfolio

## YouTube Data Scraper

<a href="https://github.com/RaphaelCaloz/youtube-data-scraper">Click here to view this project's code repository (which includes a more detailed description).</a>

This software navigates YouTube to collect video data (thumbnail images and tabular data). Since YouTube's API greatly limits the number of queries per day, it is not practical to build a dataset with it. This data scraper bypasses the API by simulating a human user navigating the website, collecting data along the way. This makes the collection of a substantial dataset practical.

<br>

<img src="https://github.com/RaphaelCaloz/youtube-data-scraper/blob/main/readme_images/data_scraper_animation.gif" width="720"/>

_The data scraper navigating YouTube._

<br>

## Full Stack Comic Strip Web App

<a href="https://github.com/RaphaelCaloz/web-app-comic-strips">Click here to view this project's code repository (which includes a more detailed description).</a>

<a href='https://raphael-caloz-comic-strips.herokuapp.com/'>Click here to view this project's website.</a>

This web app, hosted on Heroku, displays comic strips.
Its backend is built with Express (Node.js web application framework) and features a REST API, while its frontend is built using React.
This web app makes HTTP requests to the <a href='https://xkcd.com/json.html'>XKCD API</a> to get data about comics. The data are then processed and finally displayed with React components.
Each comic strip's view count on the website is kept track of by storing data in and making queries to a PostgreSQL database.

<br>

<img src='https://github.com/RaphaelCaloz/web-app-comic-strips/blob/main/readme_images/website_animation.gif'/>

_The live web app._
