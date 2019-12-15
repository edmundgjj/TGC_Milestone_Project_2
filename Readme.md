# Jimbo's Movie Search #

### Interactive Front End Development Project - Code Institute ###
By: Jimmy Hsu

## Demo
A live demo of the finished project can be found [here](https://papadum-is-nice.github.io/TGC_Milestone_Project_2/).

![Desktop Demo](https://github.com/papadum-is-nice/TGC_Milestone_Project_2/blob/master/Images/JimboMovieSearch.gif)

## Aim ##

I have worked in the broadcast media industry almost my entire career and making TV programmes is my passion. Also, I am a movie buff and frequently search for additional information about the movies that I have watched. This is probably where the inspiration for this project came from because I am sure that there are many other like-minded people who would like a quick and easy way to access to detailed information on films of their choice.

## UX ##
This project was designed starting with a mobile-first approach, with adjustments for medium and larger sized screens. I wanted the website to look inviting, resembling a posh, cosy movie theatre. The information given to the users is not over-whelming, but straight to the point with added resources if they would like to find out more.

I chose a dark theme for this website because the lighting in movie theatres are mostly very warm,dimmed and inviting. There are plush, velvety seats and I wanted to replicate this on my website with a picture of a thick, dark red curtain that we often see in theatres. The curtain background picture subtlely suggests to the user that something nice and exciting is waiting for them once they use the website's search feature.

The landing page is kept simple and minimalistic because the main aim is to have the users input a movie title and should not have too many other distractions.

I also included a collage image of some movie posters I stitched together on photoshop that links to Rotten Tomatoes' Top 10 Movies of 2019 for the users' reference.

Once the users have keyed in and submitted the movie title, the image of the 'Rotten Tomatoes' Top 10 Movies of 2019' disappears and the search results takes its place. Unfortunately, the 
OMDB api only returns a maximum of ten results but it should suffice if the user is specific with his/her search string entry . The movie search results are placed neatly side by side with a button 'movie details' that invites users to click on it for added information.

Once the button is clicked, another page is loaded which shows the details of the search. I would expect movie buffs to be visual creatures and I included the poster of the search to be prominently displayed on the left. On the right side, details of the movie is displayed in an easy to read format.

There are 2 buttons centered right below the page that takes the user back to the movie search page or on to [imdb](https://www.imdb.com/?ref_=nv_home) for additional information that was not included. The buttons are designed to be larger than usual and looks very clickable for the users should they choose to click them.

## UI ##
The [landing page](https://papadum-is-nice.github.io/TGC_Milestone_Project_2/index.html) page was designed to be warm and inviting with a touch of excitement, just like how most people feel before they enter a movie theatre. 

An input box is provided which allows the users to type in the movie or tv series of their choice. I placed the input box closer to the top, at eye level and not dead center of the screen so it is the first thing the user notices when the page is loaded.

The colors used on the elements on the landing page are chosen to not contrast the dark theme, but to compliment it.

Upon hitting enter with an input on the search box, the movie poster collage image linking to Rotten Tomatoes' Top 10 Movies of 2019 makes way for the search results to avoid unnecessary clutter for the user.

If the user clicks on the 'movie details' of the returned results, the user is brought to the [movie page](https://papadum-is-nice.github.io/TGC_Milestone_Project_2/movie.html). To be consistent with the landing page, the result page has the same inviting theatre curtain as the background picture as well. It is also dark themed so users are not jolted out of their eagerness and expectation to read the results.

The movie posters are the only elements that are bright or seemingly out of place with the dark theme but this is alright as they are part of the results and the contrast works in this context.

I included the main details of the movie such as director, writer, actors and rating as these are the frequently searched information movie buffs are looking out for.

At the bottom of the page, the users are presented with 2 buttons which allow them to find additional information of the selected movie title on [imdb](https://www.imdb.com/?ref_=nv_home) or go back to the [landing page](https://papadum-is-nice.github.io/TGC_Milestone_Project_2/) for a another title search. 

If the user chooses to go back, he/she will find that the previous search is still on the input box. This is because the local storage has stored this information temporarily.

## Wireframes ##
Wireframes were created to help me visualise the website in different sized screens. They can be viewed via this [link]().

## User Stories ##
These are the user stories that I intended to achieve while building this website:
1. To build a clean, modern looking and easy to use website
2. To build this useful website for movie buffs like I
3. To build a one-stop website where users could fulfill their need to getting additional information on movies or TV series of their choice
4. To demonstrate my skills in html, css, javascript, using APIs and other technological tools from this website 

## Features ##
* A website that looks inviting and elegant to users
* A useful and informative one-stop website that allows users to get  information on the movie they search for, and also additional results of the queried title
* An option to go to imdb's website for futher reading on their favourite movies

Future features
* I want to include movie trailers with the searches
* I want to add a page of trivia about the movie that the user has chosen to find information on
* I want to add affliated links to cinemas / movie theatres in the users' vicinity

## Technologies Used ##
Here are a list of programming languages, frameworks, technologies and tools used for this website.

* HTML5
* CSS3
* JavaScript
* JQuery
* [Axios callback](https://www.npmjs.com/package/axios) 
* Markdown in [Google Colaboratory](https://research.google.com/colaboratory/faq.html)
    * Used for writing this README.md file
* [Visual Studio Code](https://code.visualstudio.com/)
    * Used as the IDE to write the codes for this website   
* [Bootstrap 4.4.0 framework](https://getbootstrap.com/)
    * Used for it's grid system, page layout with styling and responsive navigation bar.
* [Git](https://git-scm.com/)
    * Used for version control to commit to Github
* [Github](https://github.com)
* [Google Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools)
* [Am I Responsive?](http://ami.responsivedesign.is/?url=#)
    * Used to see across multiple devices with different screen sizes the responsiveness of the website
* [Gifox](https://gifox.io/)
    * Used to capture the responsive screens into a gif file
* [W3C Markup Validation service](https://validator.w3.org/)
* [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/)
* [Esprima](https://esprima.org/demo/validate.html)    

## Testing ##
This website was tested on different web browsers and on different devices. I also requested friends and family to give their feedback. Adjustments were made after having their input.

Devices and browesers:
* MacBook Air
    * Google Chrome
    * Safari
* MacBook Pro
    * Google Chrome
    * Firefox
    * Safari
* MacPro
    * Google Chrome
    * Firefox
* Windows 10 Enterprise
    * Google Chrome
    * Mircosoft Edge
* Samsung Galaxy Core Prime, Samsung Galaxy S7 edge
    * Google Chrome
    * Samsung web browser

I used Google Chrome Devtools to view this website on a number of stimulated mobile, tablet, laptop and desktop. These include Galaxy S5, Pixel 2, Pixel 2 XL, iPhone 5 / SE, iPhone 6/7/8, iPhone 6/7/8 plus, iPhone X, iPad, and iPad Pro.

## Deployment ##
Version control was made using Git and [Github]((https://github.com)) hosts the repository for all commits

This website is deployed using Github pages. Please click on [Jimbo's Movie Search](https://papadum-is-nice.github.io/TGC_Milestone_Project_2/) to find the deployed website.

### How to save the project to a local computer ###
If you would like to run this code locally, please follow these steps: 

#### Download ####
1. Download [Jimbo's Movie Search](https://github.com/papadum-is-nice/TGC_Milestone_Project_2.git); click on green button *Clone or download* then *Download ZIP*. The repository will be downloaded on your computer
2. Right click on the file and choose to uncompress the file
3. Double click on the HTML file to view the file on your preferred browser
4. Import the other files in your IDE and feel free to make changes to them

#### Clone ####
1. Clone the repository from [(Jimbo's Movie Search)](https://github.com/papadum-is-nice/TGC_Milestone_Project_2.git)
2. Click on green button *Clone or download* and copy the URL address shown in the input box
3. Paste `git clone https://github.com/papadum-is-nice/TGC_Milestone_Project_2.git` into your IDE's terminal
4. When you want to remove the connection, type `git remote rm origin` into your terminal

## Credits ##

### API ###
1. [Omdb](http://www.omdbapi.com/) movie API

### Code ###
1. Inspired by Traversy Media’s “Build A JavaScript & jQuery Movie Info App in 30 Minutes” https://www.youtube.com/watch?v=YsPqjYGauns'
2. Theme from https://bootswatch.com/
Used and modified darkly theme 

### Images ###
1. Movie posters taken from [Rotten Tomatoes](https://editorial.rottentomatoes.com/guide/best-movies-of-2019/)
2. [Curtain background](https://www.google.com/url?sa=i&source=images&cd=&ved=2ahUKEwj6yY6h87fmAhVGXn0KHb7GBxYQjRx6BAgBEAQ&url=http%3A%2F%2Fclipart-library.com%2Ftheatre-curtains.html&psig=AOvVaw1jmD8ath4qU2vwlHtTtJHG&ust=1576507775519902)

**This is for educational use**