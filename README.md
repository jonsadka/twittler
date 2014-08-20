#twittler

Created two global variables, users and streams:
  users is an array of strings -- all the usernames that you're following.
  streams is an object with two properties, users and home.
    streams.home is an array of all tweets from all the users you're following.
    streams.users is an object with properties for each user. streams.users.shawndrost has all of shawndrost's tweets.
App kicks off a periodic process that puts more data in streams.

This is a copy of the work I did on a private repo, originally a project from
[Hack Reactor's](http://hackreactor.com) curriculum. This project was worked
on with a pair; it's representative of the kind of problems that I've tackled,
but not of my solo work.
