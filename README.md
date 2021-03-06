# Deeelish

Deeelish is a web application, designed by me, Carly Clark, to satisfy the requirements of the "Data Centric Development" milestone project on the Code Institute Full-Stack Software Development course.

It is intended to be an online community resource primarily for searching and sharing recipes, though users can also create, edit and remove categories from the collections as well as view cooking tips and techniques. 


## Demo
A live demo can be found [here](https://deeelish.herokuapp.com/).


## UX

### User Stories

As the cook of the household, I am looking for recipe inspiration for our next family dinner and would like to be able to quickly search a collection of recipes and view the recipe details. 

As a cooking novice, I would like access to recipes with step by step preparation guidance, as well as some handy tips and techniques to improve my skills. 

As someone with food intolerances, I would like to be able to filter my recipe search by specifc dietry requirements as well as my preference for the type of meal course and cuisine.

As someone with a passion for homecooking, I would like to be able to add my tried and tested recipes to the collection so they can be shared with a community of like-minded people. I would also like to be able to edit and delete my recipes if I spot an error or its no longer suitable. 


### Strategy
My goal in the design was to make it as easy as possible to access information, whether this be recipes, catergories, tips or techniques, while striving to display the information in a minimalist and user-friendly format.

### Scope
I wanted users to feel welcome, to understand the purpose of the site and to be provided with some inspiration to get them cooking. I would like users to be able to view, edit and delete the categories and recipes in the collection as well as add their own categories and recipes. Additionally I would like users to be able to access our handy tips and techniques to improve their cooking skills. 

### Structure
My hope was to present information to the users in a logical format that provides easy access to the information they require. With this in mind, users are welcomed to the site landing page with a brief overview of the purpose and some featured 'seasonal' recipe imagery to inspire them. From there, users can easily navigate to 5 other areas of the site; Discover Recipes, Add Recipe, Browse Categories, Add Category and Tips & Techniques. On the Discover Recipe and Browse Categories pages, users can choose to expand a particular result to view more detail or access options including view, edit and delete. Hiding these options until required is is intended to promote a minimalist design. 

### Skeleton
The basic wireframes for this site can be found below

Home Page
![Home Page](https://github.com/Carly07/deeelish/blob/master/static/wireframes/homepage.jpg)

Tips & Techniques Page
![Tips & Techniques Page](https://github.com/Carly07/deeelish/blob/master/static/wireframes/tipspage.jpg)

Discover Recipes Page
![Discover Recipes Page](https://github.com/Carly07/deeelish/blob/master/static/wireframes/discoverrecipes.jpg)

Browse Categories Page
![Browse Categories Page](https://github.com/Carly07/deeelish/blob/master/static/wireframes/browsecat.jpg)

Add/Edit Recipe Page
![Add/Edit Recipe Page](https://github.com/Carly07/deeelish/blob/master/static/wireframes/addoreditrecipe.jpg)

Add/Edit Category Page
![Add/Edit Category Page](https://github.com/Carly07/deeelish/blob/master/static/wireframes/addoreditcat.jpg)

View Recipe Page
![View Recipe Page](https://github.com/Carly07/deeelish/blob/master/static/wireframes/viewrecipe.jpg)

### Surface
The grey and yellow color scheme was chosen to create a bright, modern feel. Colourful images of fresh produce, cooked meals and home bakes are used to appeal to the users senses.


## Features

### Existing Features

#### Navbar
A fixed Navbar with 2 dropdown menus has been implemented on larger devices whilst a side nav is enabled for mobile use. It was felt that this would enhance user experience by ensuring quick and easy navigation whilst still promoting a minimalist design. 

#### Seasonal Recipes Section
The featured 'Seasonal' recipe imagery is displayed using a touch enabled carousel offering the users recipe inspiration. Users can click on the image to be redirected to the relevant recipe. 

#### Filter Function
A form at the top of the Discover Recipes page offers users three collections, each with dropdown menus displaying categories to select from in order to filter their recipe results. The Meals & Courses Collection and the Cuisines Collection have been populated dynamically so they remain consistant with any changes that have been made to individual categories in the database. 

#### Discover Recipe and Browse Category Pages
The Discover Recipe and Browse Category results are presented in an accordion displaying only basic details and hiding additional information that's not immediately relevant. Where users are interested in a particular recipe or category, they can expand the result to reveal more information and or other options available to them such as View, Edit and Delete. 

#### Adding and Editing a Recipe or Category
Materialzie Forms incoroparting input fields, text-areas, select menus and switches, have been used to receive user inputted data when adding or editing a recipe or category. The forms have sensible defaults for fields which are required or optional. 

#### Flash Messages
Flash messages have been implemented to provide feedback to the user when adding, editing or deleting from the database. Users will recive confirmation of a successful action or else be notified that either the category already exists when trying to add a new entry or that they cannot delete a category that is currently in use. 

#### Tips Section
Cards with a hoverable class are used to navigate users to three handy tips. If users are interested in a particular tip, they can click on the card title to open a modal displaying the information to the user. 

#### Footer
Materialize Footer has been used to provide the user with social medial links and copyright information. 


### Features Left to Implement
* User registration and authentication so that users are only able to edit and delete recipes and categories that they have added. I would also like them to be able to bookmark / save recipes that they are interested in.
* A Search Box facility on the Discover Recipes page to enable users to search for a specific recipe, ingredient or keyword. 
* An upload file facility on the Add Recipe page to enable users to add a recipe photograph rather than a URL. 
* Develop the Tips and Techniques page to include more content. 


## Technologies
All the languages, frameworks, libraries, and tools used to construct this project are listed below. I have also provided a relevant link and a brief overview of its usage.

### Languages
* <a target="_blank" href="https://en.wikipedia.org/wiki/HTML5">HTML5</a> – Used to write customised front-end content for the application.
* <a target="_blank" href="https://en.wikipedia.org/wiki/Cascading_Style_Sheets">CSS3</a> – Used to customise the style of the web application. 
* <a target="_blank" href="https://en.wikipedia.org/wiki/JavaScript">JavaScript</a> - Used to add an onclick event to my cancel and return buttons within the application.
* <a target="_blank" href="https://www.python.org/">Python</a> - Used to build the back-end functionality.


### Frameworks
* <a target="_blank" href="http://archives.materializecss.com/0.100.2/">Materialize CSS v.0.100.2</a> - A framework used to create the responsive grid system and various components within the site including the navbar, select menus, accordion, cards, modals and carousels. 
* <a target="_blank" href="https://en.wikipedia.org/wiki/Flask_(web_framework)">Flask</a> - A python microframework used to construct and render pages within the application quickly and easily.


### Libraries
* <a target="_blank" href="https://jquery.com/">jQuery</a> - A JavaScript library used here to simplify DOM manipulation when initializing specific Materialize components within the application e.g. carousel, modal, accordion etc.
* <a target="_blank" href="https://fonts.google.com/">Google Fonts</a> – The font used was obtained from Google Fonts.
* <a target="_blank" href="https://fontawesome.com/">Font Awesome</a> - The Social Media icons used within the footer were sourced from Font Awesome.
* <a target="_blank" href="https://material.io/resources/icons/?style=baseline">Material Icons</a> - All other icons used within the web application were sourced from Material Icons.
* <a target="_blank" href="https://jinja.palletsprojects.com/en/2.11.x/">Jinja</a> - A templating language used to simplify the displaying of back-end data in a HTML markup format that is returned to the user via an HTTP response.
* <a target="_blank" href="https://api.mongodb.com/python/current/api/pymongo/index.html#module-pymongo">PyMongo</a> - A driver used to access the MongoDB database from Python and make communication between the two possible.


### Tools 
* <a target="_blank" href="https://www.gitpod.io/">GitPod</a> – The online Integrated Development Environment (IDE) used for the development of this project.
* <a target="_blank" href="https://account.mongodb.com/">MongoDB</a> - A NoSQL database used for storing the user data in JSON-like documents.
* <a target="_blank" href="https://www.google.co.uk/chrome/">Google Chrome</a> - This browser and its' developer tools were used throughout the development of the app. 
* <a target="_blank" href="https://www.google.co.uk/chrome/">Responsinator</a> - Website used to test responsiveness on different devices. 
* <a target="_blank" href="https://github.com/">Git</a> – Used for version control
* <a target="_blank" href="https://github.com/">GitHub</a> – GitHub was used for hosting my repository
* <a target="_blank" href="https://github.com/">Heroku</a> – A cloud platform used for deployment
* <a target="_blank" href="https://validator.w3.org/">W3c Markup Validation Service</a> - The HTML code for this project was checked and validated by the W3c Markup Validation Service
* <a target="_blank" href="https://jigsaw.w3.org/css-validator/">W3c CSS Validation Service</a> - The CSS code for this project was checked and validated by the W3c CSS Validation Service


## Information Architecture

This project utilizes the NoSQL database [MongoDB](https://account.mongodb.com/account/login).

### Data Storage Types

The types of data stored in MongoDB for this project are:

`ObjectId`

`String`

`Boolean`

### Collections Data Structure

The deeelish project relies on three collections; recipes, meals_courses and cuisines. Examples of documents from each can be found below.

#### Recipes
![recipes](https://github.com/Carly07/deeelish/blob/master/static/images/recipescollection.png)

#### Meals and Courses
![meals_courses](https://github.com/Carly07/deeelish/blob/master/static/images/meals_coursescollection.png)

#### Cuisines
![cuisines](https://github.com/Carly07/deeelish/blob/master/static/images/cuisinescollection.png)

As can be seen above, the `ObjectId` from the specified meals_courses and cuisines category are retrieved and stored as the value for meal_course_type and cuisine within the recipe document in the recipes collection. This creates a relationship between the collections which means that if a particular category within either the meals_courses or cuisine collections is updated it will reflect the change in all the recipe documents associated with that category.

All category names are stored in lowercase within the meals_course and cuisines collections so to assist when checking for duplications. I have however, applied the `.title()` method when displaying the category names within the application to improve user experience. 

Values for the Vegetarian, Vegan, Gluten Free and Dairy Free switches are converted to `Boolean` values for storing in the database. This helped with the filter functionality on the Discover Recipes page. 

## Testing
### Developer tools

GitPod's preview, google chrome developer tools and responsinator were utilised throughout the development of the project to identify and successfully address any bugs, errors or style issues affecting UX on various screen resolutions. 

### Automated Testing
W3c Markup and CSS Validation Services were also used to check the validity of my HTML and CSS code.  **NB.** the W3c validator throws errors in the HTML files the Jinja templating syntax is found. 

### User scenarios

#### Cook of the Household
As desired, the cook of the household was inspired by the collection of recipes available at Deeelish. They arrived at the site and were immediately presented with recipe imagery that appealed to their senses. With one click on either the **Discover Recipes** link in the Navbar or the **Search Recipes** card under the welcome message, they were presented with the full collection of recipes available, displayed on an accordion showing the Recipe Name, Meal Course and Cuisine. From there, they were able to click on the expand more icon to view a short recipe description and select the **View** button to access the full recipe. 

#### Cooking novice
The cooking novice was pleased to find a full list of ingredients and step-by-step intructions as to how to prepare the recipe when they navigated to view a recipe. They were also able to access the **Tips and Techniques** page from anywhere on the site using the link on the navbar and this provided them with some handy guides and videos to help improve their cooking skills. 
The user was able to click on each Tip card to read the information on a pop out modal and then click **Close** once finished. In the Technique section, the user was able to view the video by clicking the play icon. 

#### User with food intolerances
The person with food intolerances achieved their desired outcome of filtering the recipe results by specifc dietry requirements as well as their preference for the type of meal course and cuisine by navigating to the **Discover Recipes** page. There, they were presented with three dropdown select menus; **Suitability**, **Meals & Courses** and **Cuisines** each displaying a list of options. The user was able to select an option from either one, two or all three menus before clicking the **filter** button to retrieve the list of results available. Equally, they were able to retrieve the full collection of receipes by setting all 3 menus to 'All' and clicking the filter button again.

#### User with a passion for cooking
The user with a passion for homecooking, was able to add their own recipes to the collection for sharing with the Deeelish community. They were able to achieve this by clicking on either the **Add Recipe** link from the menu or the **Share Recipe** card on the home page under the welcome message. This provided them with a simple form to input their recipe and a button to **Submit Recipe**. If the user tried to submit the recipe without key fields being complete, they received a prompt advising that the information was required. Having successfully submitted the recipe, the user received a confirmation message. 

This user was also pleased to find, having viewed the recipe and spotted an error, that they were able to edit the recipe by clicking on the **Edit** button at the end of the recipe. This presented them with a pre-populated form similar to the Add Recipe page. The user was able to update the required fields and click **Save Changes** to update the recipe. 

Similarly, having changed their mind about a particular recipe entry, they could click on the **Delete** button located at the end of the recipe. The user was provided with a confirmation message for each edit and delete action completed. 

Additionally, this user was able to **View**, **Add**, **Edit** and **Delete** categories in both the Meals & Course and Cuisines collections by navigating to the **Browse Categories** link in the menu. There, they were presented with a button at the top to **Add New Category** followed by the results for both collections, each with the option to **Edit** or **Delete** when the expand icon was clicked. 

When they selected to add a new category, they were redirected to a form containing the collection names as subheadings, an input field below each for their entry and a button to **Add Category**. If successful, they received a confirmation message but when the category already existed in the database, they receive a message advising them so and the category was not added to the collection. 

Similarly when they opted to edit a category they were taken to a short form with the collection heading, a pre-populated input field ready for editing and a **Save Changes** button to update the database. The user then received a confirmation message that the category had been updated and they were able to see their result on the Browse Category page as well as in the dropdown menus on the Discover Recipe, Add Recipe and Edit Recipe pages. 
Users were also able to delete a category and observe the result in this way, but if they tried to delete a category that was already being used by a recipe, they recieved a message advising them so and the category was not deleted from the collection.   

### Multiple browsers and devices

After the site was deployed, I tested it across four browsers (Chrome, Safari, Internet Explorer, FireFox) and on multiple devices (Samsung Galaxy J3, iPhone 7 Plus, 8, iPad 6, iPad Air, MacBook Air and iMac) as well as on Responsinator to ensure compatibility and responsiveness. 

Whilst testing, I noticed that the parallax images were not displaying correctly on my iphone. Having researched the problem, I found that using a media query to adjust the height fixed the issue. I also found that the required attribute did not work with on the Select dropdown menus. Having searched the internet, I quickly realised that Materialise does not cater for the required attribute. I tried several work-arounds but did not get the desired finish I was after so I decided to change the select menus to the browser-default.


## Deployment
This application was deployed to Heroku for hosting. 

In order to achieve this, a `requirements.txt` and `Procfile` were created using the following two commands in the terminal:

`pip freeze > requirements.txt`

`echo web: python app.py > Procfile` 

A new app was created on the Heroku website by clicking the **New** button on dashboard. The app was named deeelish and the region set to Europe. Then, from the **Deploy** tab on the deeelish app dashboard, the "Deployment method" was set to GitHub and the "Manual Deployment" section was set to master branch before clicking **Deploy Branch**.

All code was then committed to a local Git repository using the `git add` and `git commit -m 'message'` commands. The code was then pushed to a remote [GitHub repository](https://github.com/Carly07/deeelish) using `git push -u origin master` before being deployed to Heroku using `git push heroku master`. 

During development my environment variables (SECRET_KEYs and MONGDB_URIs) were stored in a seperate file (env.py) that was not pushed to my git repository so to prevent anyone (or any bot) from accessing and misusing the sensitive information. However, as heroku uses the GitHub repository code to build the app, it wouldn't have access to the environment variables and this would likely throw errors. 
So, for deployment, I gave heroku a copy of the environment variables; storing them in Key Value pairs under Reveal Config Vars in the **Settings** tab on my app dashboard. Similarly, during development, the debug attribute was set to true whilst for deployment it has been changed to false. 

### To run the project locally
To run the project locally in your own IDE, you must have Git, PIP and Python installed on your machine. You will also need to set up a MongoDB account [here](https://account.mongodb.com/account/login) and create a database called deeelish with three collections named recipes, meals_courses and cuisines. You will find example json structures for these collections under Information Architecture above. 

Once this is done, you can then simply clone my repository by pasting `git clone https://github.com/Carly07/deeelish` directly into your terminal. Next, install all the required modules with the command `pip -r requirements.txt`, then create a file called `env.py` and inside this add a SECRET_KEY variable and a MONGO_URI to link to your own database. 

You should then be able to run the application with the command `python app.py`


## Credits

### Content
* All the recipes used within this site were sourced from [BBC Good Food](https://www.bbcgoodfood.com/). 
* The text within the Tips section was taken from [BBC Good Food](https://www.bbcgoodfood.com/).

### Media
* The photographs used throughout this site were found on [Google Images](https://www.google.com/imghp?hl=en).
* The videos contained within the Techniques Section were obtained from [YouTube](https://www.youtube.com/).

### Acknowledgements

Small pieces of code have been copied from elsewhere, such as Materialize CSS. I have also made use of a number of websites in my pursuit to wire the all the functions necessary for this app, but particularly

* [Stack Overlflow](https://stackoverflow.com/)
* [W3School](https://www.w3schools.com/)
* [tutorialspoint](https://www.tutorialspoint.com/flask/index.htm)
* [Flask](https://flask.palletsprojects.com/en/1.1.x/)

Finally a special thanks to my mentor, Antonio Rodriguez, the tutors at Code Institute and the Stack community for their help and advice with this project.

**This is for educational use.** 