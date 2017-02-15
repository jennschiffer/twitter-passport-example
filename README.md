Twitter Passport Example
========================

This app is a building block for using Twitter OAuth using [passport-twitter](https://github.com/jaredhanson/passport-twitter). You will need to [create a Twitter app](https://apps.twitter.com/app/new) to obtain the keys for the `.env` variables.

## View the Code

On the back-end,
- the app starts at `server.js`
- frameworks and packages are in `package.json`
- app secrets are safely stored in `.env`

On the front-end,
- edit `client.js`, `style.css`, `index.html` and `success.html`
- drag in `assets`, like images or music, to add them to your project

## Screenshots

The index page at `/` has a link to log in via Twitter

![log in page](https://cdn.gomix.com/06290abf-71bb-4336-9447-5364c4b2b6d6%2Findex.png)

On successful authentication, a cookie is set and you're redirected to `/success`
![successful authentication](https://cdn.gomix.com/06290abf-71bb-4336-9447-5364c4b2b6d6%2Fsuccess.png)

When clicking the log off link, the cookie is deleted and you're redirected to back to the index page at `/`


Made by Fog Creek
-----------------

\ ゜o゜)ノ
