# config/session.js

This file contains information that tells Sails where to store your sessions.

Sails session integration leans heavily on the great work already done by Express, but also unifies socket.io with the Connect session store. It uses Connect's cookie parser to normalize configuration differences between Express and socket.io and hooks into Sails' middleware interpreter to allow you to access and auto-save to `req.session` with Socket.io the same way you would with Express.

This is where you would go to configure a different session store like Redis or Mongo.  In this file you will find commented examples of what that configuration should look like.

This file also contains your 'Session Secret' that is generated by Sails when you create your app.  Do not change or remove this unless you really know what you are doing.

### Usage

See [`sails.config.session`](https://sailsjs.com/documentation/reference/configuration/sails-config-session) for all available options.


<docmeta name="displayName" value="session.js">