# News Sentiment Analysis with MeaningCloud

**A web tool that allows users to run Natural Language Processing (NLP) on articles or blogs found on other websites.**

This is a single-page web application which uses [MeaningCloud](https://learn.meaningcloud.com/developer/sentiment-analysis/2.1/doc) sentiment analysis API to perform qualitative assesment of a user's entered news item.

This project demonstrates the following front end web development skills:

-   Setting up Webpack
-   Sass styles
-   Webpack Loaders and Plugins
-   Creating layouts and page design
-   Service workers
-   Using APIs and creating requests to external urls with fetch
-   Using Express to set up a back end server

<img src="https://user-images.githubusercontent.com/74114444/162404603-d838f1ad-2692-4cb1-8222-839dd375ed2c.png" width="450">


## Project Requirements

This project is part of Udacity Front End Web Development Nanodegree. The requirements are:

-   [x] Be set up with Webpack, Express, Node, and Sass, and Service Workers
-   [x] Have separate dev and prod configurations for Webpack
-   [x] Have the developer environment set up with the Webpack dev server
-   [x] Have a minimum of one form field
-   [x] Make one request to the MeaningCloud API
-   [x] Use Sass for styling
-   [x] Minify js and styles in the production environment
-   [x] Response from the API must be added to the view for a user to see
-   [x] Be able to show content offline

See [project rubric](https://review.udacity.com/#!/rubrics/3626/view) for more.

## Dependencies

You need [Node.js](https://nodejs.dev/) and npm installed on you computer.

## Getting started

1. Clone this repo to your local machine.

2. Run `npm install` in the project folder on your local machine.

3. Sign up for [MeaningCloud account](https://www.meaningcloud.com/developer/create-account). An API key will be accessible in your profile.

4. Create a `.env` file in the root of your project and paste your API key in it like this:
   `API_KEY=your-api-key`

## Production mode

-   Make sure you have run `npm install`.
-   In the terminal, run `npm build` followed by `npm run start`.
    The app will run on port 5000.

## Development mode

-   Make sure you have run `npm install`.
-   In the terminal, run `npm build-dev`.
-   Open up a second terminal window and execute `npm run start` (this is needed to execute the API request on the server side).
-   The app will automatically launch on Webpack Devserver on port 8080.

## Deploying

This project is deployed at [https://news-evaluation.herokuapp.com/](https://news-evaluation.herokuapp.com/)

## Testing

-   Run `npm install` if you haven't yet to install project dependencies
-   Run `npm test` to execute the unit tests.
