# How to create a basic Symfony app with Vue.JS and Twilio

A full-stack application for utilizing Twilio product using Symfony and Vue.js. You can read more [here](https://www.twilio.com/blog/create-single-page-application-symfony-vue-js-twilio-php).

## How to install

- Clone this repository and then change your current directory to the root folder of the project.

- Create the `.env` file:

    ```bash
    $ cp .env.example .env
    ```

- Next, install the back-end dependencies:

    ```bash
    $ composer install
    ```

- Next, open a new terminal and then run the below command to install the front-end dependencies:

    ```bash
    $ yarn install
    ```

- Now start up the back-end server:

    ```bash
    $ php -S localhost:9030 -t public
    ```

- Then finally, start up the front-end development server so that the changes we make to the Vue files will be compiled automatically:

    ```bash
    $ yarn encore dev-server --hot
    ```
And that's it! You can now access the app from [http://localhost:9030](http://localhost:9030)
