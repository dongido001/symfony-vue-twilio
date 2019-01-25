# How to create a basic Symfony app with Vue.JS and Twilio

A full-stack application for ustilizing Twilio product using Symfony and Vue.js. You can read more [here]().

## How to install

- Clone this repository and then change your current your directory to the root folder of the project.

- Create the `.env` file:

    ```bash
     $ cp .env.example .env
    ```
    
- Next start up the backend server:

    ```bash
    $ php -S localhost:9030 -t public
    ```

- Finally, start up the frontend development server so that changes we make to the Vue files will be compiled:

    ```bash
    $ yarn encore dev-server --hot
    ```
You can access the app from [http://localhost:9030](http://localhost:9030)
