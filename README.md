# move2diaspora

This is a lil facebook-to-diaspora migration tool that has been useful in my friend circles. The idea is that you can see all your friend's diaspora usernames that have already used it. You go there, save your diaspora username, and you & your friends can see each other listed, so you can add each other to diaspora. See it running, [here](http://move2diaspora.herokuapp.com/).

## todo

Here are things I will eventually implement:

*  Unfortunately, facebook won't let an application get your entire friend-list, just the friends that have used the app, but I will look into working around it.

## installing your own

[deploy your own on heroku](https://heroku.com/deploy?template=https://github.com/konsumer/move2diaspora)

You need to setup a new facebook web app and set these environment variables in the app's environment variables:

    MONGOLAB_URI=mongodb://BLAHBLAHBLAH
    FACEBOOK_APP_ID=BLAH
    FACEBOOK_APP_SECRET=BLAHBLAH