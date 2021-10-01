# Mistral Movies App

-First of all, you need to do the few things listed below before you can properly start the application. 

-After you cloned the project, open the folder “MovieRating.API ”, open the .sln , and in Package Manager Console type “update-database” to seed data into a database.
 After that, start the project with (F5, ctrl F5). That project is API and on the startup, it will be Swagger with implemented endpoints ready for testing and use. 

-After you started the Web API project, now you can open the folder “movie-rating-react”. Open this folder in Visual Studio Code.
 Open Terminal and use the command below for installing workspace npm dependencies:
 

    npm install


-After the installation of all required npm dependency packages, for starting application in the same Terminal type command:


    npm start


-It will provide URL: http://localhost:3000/  copy that URL and past it into a new tab in Browser

#NOTES 

Browser will  open application and on initial screen we have Navigation with two Nav links: Home and Rate Movies.
When user click on Home link, it will open page which have two tabs. One tab is for Movies and other one is for TV Shows.
When user click on Rate Movies link, it will open page with loaded all of Movies and TV Shows together and on that page user have possibility to rate Movies by clicking one of stars.
