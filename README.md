Welcome to Vueniverse!
===================
<img height="300px" src="https://cdn.rawgit.com/rlindskog/vueniverse/master/template/src/client/assets/img/vueniverse_logo.svg"/>
Vueniverse is a full-stack JavaScript starter project. Some of the features that comes baked in include:

 - PWA by default, 100 lighthouse PWA score.
 - Universal es2015 JavaScript.  No more context switching between client/server code!
 - A REST API, and full user authentication.
 - Client Side routing, Server Side Rendering and Global State Management thanks to Vuejs and Nuxtjs!
 - Abstracted WebPack build process.
 - Universal HMR for a clean development process, thanks to Nuxtjs and BackPack.
 - Ready for deployment with [NOW](https://zeit.co/now)

[Live Demo](https://vn-src-zlrdxjkdrb.now.sh/)

*You must have [vue-cli](https://github.com/vuejs/vue-cli)* installed.

    npm install -g vue-cli

**Create Project**

    vue init rlindskog/vueniverse {{ your-project-name }}
    cd {{ your-project-name }}
    npm install

**Create and run a MongoDB database (in a seperate terminal window)**

    mkdir ./db
    npm run dev-db

**Run in development**

    npm run dev

**Build for production**

    npm run build

**Run in production - uses [pm2](https://github.com/Unitech/pm2)**

    npm run start

**Stop production processes**

    npm run stop

**Deploy with [NOW](https://zeit.co/now)**

    npm install now-cli
    rm -rf ./db

You will have to make run a database else where in paste the link to it in .prod.env DB_URL.  Then run...

    now

**FUTURE TODO**
 - vue-cli option to choose bewteen PostgreSQL and MongoDB (MongoDB currently implemented)
 - vue-cli option to choose bewteen AirBNB and Standard Linting Style.
 - vue-cli option to include tests.
 - Create an admin interface!
 - Create a few more NPM convenience commands, such as "create-super-user" and "create-module" (MVC module in the REST API + Admin interface page).
 
**Pull requests welcome!**
