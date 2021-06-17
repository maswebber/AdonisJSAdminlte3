# Welcome to AdonisJSAdminLTE3

AdonisJSAdminLTE3 is Javascript framework [AdonisJS](https://docs.adonisjs.com/guides/introduction) intergrated with theme template [AdminLTE 3](https:///adminlte.io)


# How to use ?
Clone this repository :

    git clone https://github.com/maswebber/AdonisJSAdminlte3.git
    cd AdonisJSAdminlte3
    npm install
    npm run dev //For local development
    npm run build // For build production
**Don't Forget** 
Edit `.env` file on root project. 
For some reason AdonisJS doesn't copy the `.env` file when build production , so copy your `.env` to build folder manually.

Project Structure

    AdonisJSAdminLTE3
    ├── app
    ├── commands
    ├── config
    ├── contracts
    ├── providers
    ├── public
    │   ├── assets
    │   ├── dist
    │   ├── plugins
    │   └── favicon.ico
    ├── resources
    │   ├── css
    │   ├── js
    │   └── views
    │       ├── errors
    │       │   ├── not-found.edge
    │       │   ├── server-error.edge
    │       │   └── unauthorized.edge
    │       ├── layout
    │       │   ├── dashboard.edge
    │       │   ├── navbar.edge
    │       │   └── sidebar.edge
    │       ├── page
    │       │   └── home.edge
    │       └── welcome.edge
    └── start

All static assets for AdminLTE 3 inside `public` folder. If you want add your custom javascript, you can add inside `public` or `resources/js` folder and add `@entryPointScripts('your-js-file-name')` to your edge page you want tu use.
