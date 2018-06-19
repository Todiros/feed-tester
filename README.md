# The Feed Tester (JS testing w/ Jasmine)
##### *A Udacity FEND Project*

## About The Project

JavaScript testing project using the [Jasmine](https://jasmine.github.io/) framework. Part of Udacity's [Front End Nanodegree](https://eu.udacity.com/course/front-end-web-developer-nanodegree--nd001) program (Project 5). 

## Setup

See the project [HERE](https://todiros.github.io/tester/). 
    
Alternatively, you can host it yourself by running `index.html` with `js`, `css`, `jasmine` and `fonts` folders on a web server.  

## Testing

The project consists of 4 test suites with total of 7 tests for the main features of the application: 

#### RSS Feeds

* __are defined__ - Checks whether the `allFeeds[]` variable has been defined and it is not empty.
* __all URLs defined and not empty__ - Loops through each feed in the `allFeeds[]` array and ensures it has a `URL` defined and that the `URL` is not empty.
* __all Names defined and not empty__ - Loops through each feed in the `allFeeds[]` array and ensures it has a `name` defined and that the `name` is not empty.

#### The menu

* __menu hidden__ - Test that ensures the menu element is hidden by default.
* __menu toggles on click__ - Test that ensures the menu changes visibility when the menu icon is clicked.

#### Initial Entries

* __loadFeeds has loaded a feed__ - Checks whether the `loadFeed()` function is called and completes its work, as well as that there is at least a single `.entry` element within the `.feed` container after it's completion.

#### New Feed Selection

* __content changes when new feed has been loaded__ - Test that ensures when a new feed is loaded by the `loadFeed()` function, the content actually changes.

## Technology

* JavaScript (ES6) w/ [jQuery](https://jquery.com/)
* [Jasmine Framework](https://jasmine.github.io/)
* CSS
* HTML w/ [Handlebars.JS](https://handlebarsjs.com/)

## Dependencies 

It uses [Jasmine Framework](https://jasmine.github.io/) for the JavaScript testing. 

## Credits

* Core project files (app, css and fonts) provided by [**Udacity**](https://eu.udacity.com/)
* Tests: [**Me (Anthony D. Borr)**](http://todiros.github.io/adb/)
* Resources: 
    * Testing Framework: [**Jasmine**](https://jasmine.github.io/)
    * Coffee: [**Tchibo**](https://www.tchibo-coffee.co.uk/)