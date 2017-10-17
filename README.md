# API Framework

This is a framework for building REST APIs based oni [Scott Domes' tutorial](https://medium.freecodecamp.org/building-a-simple-node-js-api-in-under-30-minutes-a07ea9e390d2).

It uses the following:
- node
- express
- mongoose
- cors
- body-parser

To get it running, all you need to do is plug in your own MongoDB url in `config/db.js`, then from the project root run `npm start APPNAME PORT`, replacing APPNAME with the name defined in `package.json` and PORT with the port number to listen on.

This comes with a basic mongoose Model and functioning POST, GET, PUT, and DELETE endpoints.

Much credit to Scott Domes for the great tutorial.
