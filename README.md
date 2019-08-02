<h1 align="center">
<br>
  <img src="static/img/veggit-1.png" width="600">
  <br>
    <br>
  Online Cookbook
  <br>
</h1>

<h4 align="center">A web application that allows users to store and easily access cooking recipes.</h4>

This project is a fictional service, based on a real-world application, which offers a practical user-experience.

## Table of Contents

<!--ts-->

- [About](#About)

  - [Goal](#Goal)
  - [Functionality (User Stories)](#Functionality-User-Stories)
  - [Initiation](#Initiation)

- [UX](#UX)

  - [Layout Pro](#Layout-Pro-Boundless-Adaptability)
  - [Layout Con](#Layout-Con-Moderate-Speed-and-Execution)
  - [Tablet Display](#Tablet-Display)
  - [Mobile Display](#Mobile-Display)
  - [Additional Note](#Additional-Note)
  - [Colour Scheme](#Colour-Scheme)
  - [Font](#Font)
  - [Navigation](#Navigation)
  - [Database Structure](#Database-Structure)

- [Technologies](#Technologies)

  - [Languages Frameworks Tools](#Languages-Frameworks-Tools)
  - [Other-Resources](#Other-Resources)

- [Features](#Features)

  - [Existing Features](#Existing-Features)
  - [Features-Left-to-Implement](#Features-Left-to-Implement)

- [Testing](#Testing)

  - [Tools-and-Methods-Used-for-Testing](#Tools-and-Methods-Used-for-Testing)
  - [Additional-Points](#Additional-Points)
  - [Tested Sections 1](#Tested-Sections-1)
  - [Tested Sections 2](#Tested-Sections-2)

- [Deployment](#Deployment)

  - [How the project got deployed to Heroku](#How-the-project-got-deployed-to-Heroku)
  - [Cloning the repository](#Cloning-the-repository)
  - [How to access the live application](#How-to-access-the-live-application)
  - [How to run things locally](#How-to-run-things-locally)

- [Credits](#Credits)

  - [Content](#Content)
  - [Acknowledgements](#Acknowledgements)
    <!--te-->

## About

An **Online Cookbook** web application that allows users to store and easily access cooking recipes.


#### Goal

Create a web applications which enables users to create, read, update and delete (CRUD) their online cookbook. Users can fabricate their recipe database by collecting recipes on the web and utilising the apply features. The application can be used by non-enrolled users who can use the app for browsing or the individuals who sign up for an account which allows access to the majority of the CRUD highlights.

The core focus of this project is on functional app logic created with **Python** while utilising the **Flask** framework and **MongoDB** NoSQL database.

#### Functionality (User Stories)

#...

#### Initiation

Research to understand what apps of similar scope were already doing in terms of functionality which provided me with a list of what I consider to be feasible options for functionality implementations to acknowledge and consider pre-production.

[**To top**](#Table-of-Contents)

## UX

#### Layout Pro (Boundless Adaptability)

- Choosing a **multiple page application (MPA)** takes into consideration the choice to make new content and spot it on new pages. Multi-page applications can incorporate as much data as required, for this situation, numerous tickets, name enrolment page, donations page, account profile, with no page confinements. To say it necessarily, because there is a fair amount of content and features included on the application, I feel that an **MPA** is the best decision.

#### Layout Con (Moderate Speed and Execution)

- Being as this is a multi-page application, a server needs to reload most assets, for example, HTML, CSS, and **Python** with each interaction. When loading another page, the browser completely reloads page information and downloads all assets once more, even rehashed segments throughout all pages (for example the header/navigation) which influences Speed and Execution.

#### Tablet Display

- Please note, except a slight difference in page/scale responsiveness, desktop applies the same UI.

<img src="static/img/veggit-desktop.png" width="600">

<img src="static/img/veggit-desktop-2.png" width="600">

#### Mobile Display

- This image animation represents the standard UI across most modern mobile devices.

<img src="static/img/veggit-mobile.png" width="600">

<img src="static/img/veggit-mobile-1.png" width="600">

#### Template Style

Opted for a neutral style template with a pencil type design to project a more industrial look to the application whic was acheived via use of Bootstrap and [Bootswatch](https://bootswatch.com/ "Bootswatch Official Site")

#### Font

- Being as the website modelling is off a space theme, a pencil typeface choice was selected; thus, helping to emphasise a rough industrial theme to the displayed text content; a subjective opinion, of course.

#### Navigation

- Fixed navigation makes it easier for users to browse the website and increase retention: In some ways, it's a passive call to action; always visible, always available.

- Maintaining the logo visible increases brand value. Today there is an enormous number of apps, many with identical or similar features, so I feel that it’s vital to make a good impact on users and retain their interest, which can be all linked to a good brand image.

#### Database Structure

```console
recipes {
_id: 5d433657ddab2ebc9620c441
allergens: Array
diet: ""
cuisine: ""
ingredients: Array
method: Array
author: "string"
recipe: "string"
image: "https://www.bbcgoodfood.com/sites/default/files/styles/recipe/public/r..."
email: "string"
views: 10
likes: 3
dislikes: 0
time: "string"
date: "string"
}

users {
_id: 5d2dff3f9398ee10830e15f7
email: "string"
password: "string"
}

```

[**To top**](#Table-of-Contents)

## Technologies

#### Languages Frameworks Tools

- [HTML](https://www.w3.org/TR/html5/ "HTML5 Official Site")

  - Semantic markup language utilised as the shell of the site.

- [CSS](https://www.w3.org/Style/CSS/ "Cascading Style Sheets Official Site")

  - It is Cascading Style Sheets as the design of the site.

- [Python](www.python.org)

  - I have utilised to compose the game logic.

- [Flask](https://flask.palletsprojects.com/en/1.0.x/)

  - Python web framework, library used for developing web applications.

- [MongoDB](https://www.mongodb.com/)

  - NoSQL database program, to implement a data-store using JSON-like documents with schema. 

- [Jinja2](http://jinja.pocoo.org/docs/2.10/)

  - Utilised to render HTML templates, imparting between front-end and back-end.

- [jQuery](http://jquery.com/ "jQuery Official Site")

  - HTML document traversal and manipulation, event handling.

- [javascript](https://www.javascript.com/ "Javascript Official Site")

  - Used to create responsive, interactive elements for web pages, enhancing the user experience.

- [Materialize](https://materializecss.com/ "Materialize Official Site")

  - Utilised for developing the entire UI and consistent throughout

- [Google Fonts](https://fonts.google.com/ "Google Fonts Official Site")

  - Saira font applied across the entire website

- [Font Awesome](https://fontawesome.com/ "Fontawesome Official Site")

  - Source for all utilised icons

  #### Other Resources

- [w3schools](https://www.w3schools.com/)
- [Stack Overflow](https://stackoverflow.com/)
- [Slack](https://slack.com/)

[**To top**](#Table-of-Contents)


## Features

#### Existing Features

1. Enrollment and login 

2. View every one of the plans 

3. Channel and sort plans 

4. Search through every one of the plans dependent on a catchphrase 

5. Various select menus that permit barring plans containing certain allergen/allergens 

6. Enlisted clients can include plans 

7. Enlisted clients approach their very own Cook Book. Where they can see, alter and erase their plans 

#### Other Features

Recipes get added to the application by means of a dynamic structure, that permits to: 

- Include/erase fixings/steps. 
- Include an image for every recipe recipe 
- Checkboxes that match allergens that the recipe contains 
- Pick an eating diet or cuisine

#### Features Left to Implement

- Upgrade current and add additional sifting features
- Include tags on the recipe view page which contains a word or two offering additional recipe related details.
- Add the likelihood to include more than one picture or give pictures to each progression. 
- Include remarks area plans 
- Add capacity to transfer user photographs 
- Add capacity to alter user profile, change the username, password or email.

## Testing

#### Tools and Methods Used for Testing

- HTML

  - [Freeformatter](https://www.freeformatter.com/)

  - [The W3C Markup Validation Service](https://validator.w3.org/)

- CSS

  - [The W3C Markup Validation Service](https://jigsaw.w3.org/css-validator)

- Python

  - [Python Formatter](https://pythoniter.appspot.com/)

  - Phones

  - Galaxy Note 3 (simulation and actual device)
  - Galaxy Note 9
  - Galaxy S5
  - Galaxy S9/S9+
  - iPhone 5/SE
  - iPhone 6/7/8 (simulated and real device)
  - iPhone 6/7/8 Plus
  - iPhone X
  - LG Optimus L70
  - Microsoft Lumia 550
  - Microsoft Lumia 950
  - Nexus 5X
  - Nexus 6P
  - Nokia 8110 4G
  - Pixel 2
  - Pixel 2 XL

- Tablets
  - iPad (simulation and actual device)
  - iPad Mini
  - iPad Pro (10.5-inch)
  - iPad Pro (12.9-inch) (simulated and real device)
  - Kindle Fire HDX
  - Nexus 10
  - Nexus 7

* Laptops

  - MacBook Pro (simulated and real device)
  - Asus UX 305 (simulation and actual device)

* Televisions
  - 1080p Full HD Television (simulated and real device)

- Website responsiveness was also tested by resizing the window with every addition of a new code sequence.

#### Tested Sections 1 HTML & CSS

- External links to third party websites and code authors GitHub repository.

- Checked button sizes so, they were responsive and large enough to be clicked.

- Ensured individual section headers resized and appeared well when viewed on various device screens and added opacity to the navigation bar to allow for more visibility of section header area on smaller devices.

- Spell checked all text content.

- HTML and CSS validation via [w3.org](https://www.w3.org/ "W3C Official Site").

- Checked margins and padding of the container (sections) to ensure the content within it did not look disproportionate on various screen sizes, individually smaller devices.

#### Tested Sections 2 Python

Manual testing was embraced for this application and acceptably passed. An example of the tests directed are as per the following:

- Tested route catches and hyperlinks all through the page.
- Tested the rationale of the application by looking at expected conduct against the database record information.
- Tested the responsiveness of the application on various programs and after that utilising multiple gadgets.

[**To top**](#Table-of-Contents)

## Deployment

#### How the project got deployed to Heroku


1. Go to [Heroku](https://dashboard.heroku.com/) website.
2. Select application (online-cookbook-sipo)
3. In the **Deployment Method** section, check to see if the application is already connected to GitHub. If not connected then click the relevant button to link the Heroku website to the dashboard.
4. In the **Automatic Deployment** section enable **Automatic Deploys** (optional).
5. In the **Manual Deploy** section, set the branch to **master** then click **Deploy Branch.**

#### Cloning the repository

1. Open Git Bash
2. Change the present working directory to the area where you wish to place the cloned directory.
3. Clone the repository or use the link below.

```console
git clone https://github.com/sipostudent/Milestone-Project-3.git
```

Deploy your changes, make some changes to the code you just cloned and deploy them to Heroku using Git.

#### How to access the live application

- A live demonstration is accessible by clicking [here](http://online-cookbook-sipo.herokuapp.com/ "Live Demonstration: Veggit - Online Cookbook").

#### How to run things locally


1. Download the project onto a PC and open with a source-code editor.

2. In the run.py file set the IP address and the PORT to the following: :computer:

```console
'IP', '127.0.0.1'
```

```console
'PORT', '5000'
```

3. Install all of the prerequisites shown in the requirements.txt file via opening a Command-line interface (CLI) and navigating to the project root or by opening an integrated terminal and entering the following command:

```console
pip install -r requirements.txt
```

4. Initiate the app by entering the following command into a relevant terminal:

```console
python run.py
```

5. A message in your terminal will inform you that the project is now running with the following message:

```console
Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
```

6. To display the project, open the above URL (localhost:5000) 

[**To top**](#Table-of-Contents)

## Credits

#### Content

- Except for the app (online cookbook) recipes, all written content is original and created by the code author (Sipo Charles).

#### Media

- The source of all recipes utilised in the development phase of the app is  [bbcgoodfood.com](bbcgoodfood.com/recipes).

#### Acknowledgements

- I received inspiration for this project from visiting [thecookbookapp.com](https://thecookbookapp.com/), but mostly from my interaction with other students on Code Institute's Full Stack Software Development Programme.

#### Disclaimer

This project is for educational purposes only.

[**To top**](#Table-of-Contents)