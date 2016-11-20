# Koa Boilerplate

Yet another Koa boilerplate for Koa 2 with async/await syntax sugar.

# Dependencies

    - Node.js (6.x+)
    - Yarnpkg (or npm)
    - Mongodb

# Install Dependencies

    yarn global add nodemon forever
    yarn

or

    npm install -g nodemon forever
    npm install


# Run Development Server

    make dev
or

    nodemon

# Run Staging Server

    make staging


# Run Production Server

    make production


# Watch Production Processes

    forever list

# Environment Variables for Development

    PORT        - server port; default: 3000
    NODE_ENV    - environment mode; 'production' for production, otherwise for others
    LOG         - log file name, default value: koa-boilerplate.log
