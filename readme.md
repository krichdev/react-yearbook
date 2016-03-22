#React Yearbook

As WDI comes to a close, what better way to celebrate than with a yearbook... of random people? Let's try incorporating the React Router with a random user API.

##Getting Started

* Fork and clone this repository
* Run `npm install` to install all dependencies
* Run `gulp`
  * This command will run tasks to transpile an existing React app
* Run `nodemon` in a separate terminal tab
  * This command will run the Express server needed to view the app
* Take a look at the existing app

The current application interacts with https://randomuser.me at two different API endpoints:

* `/api/people` - returns 50 people
* `/api/people/:idx` - returns a person at a particular index (0-49)

Try taking a look at the results and see what else the API returns.

##Requirements

* Incorporate React Router so that each person routes to a new page
  * Each person's name should link to a "show" page
  * Suggested route: `/people/:id`
  * Each "show" page should have a link to go back to the home page

##Suggested Process

* Install `react-router`
* Include dependencies
  * Documentation is your friend. https://github.com/reactjs/react-router
* Identify the routes you'll need to create, and setup the app to use `react-router`.
* Test the routes with some of the preexisting components
* Incorporate links and route params

##Bonus

* Add two additional pages
  * `/about`
    * Give some information about the (nonexistent) school
  * `/superlatives`
    * Query the Random User API again to retrieve random users (remove the seed). Then, assign random superlative awards
    * This may involve creating an additional endpoint
    * Superlative ideas:
      * Best dressed
      * Weirdest smile
      * Top competitive eater
