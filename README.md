ionic-site
==========

Repo for the ionicframework.com site


gulp watch uses LiveReload. You may have to up your max file limit with the following command:

    ulimit -n 5000


## Local Build

    jekyll serve -w

    npm install

    sudo npm install -g gulp

    gulp watch

    http://localhost:4000/

## Deploy

Install [heroku-toolbelt](https://toolbelt.heroku.com/) or with homebrew

```bash
brew install heroku-toolbelt
```

Then log into  heroku

```bash
heroku login
# enter your email and password when promted
```

Then add the heroku remote

```bash
git remote add heroku https://git.heroku.com/ionic-site.git
```

- Make your changes
- Run `gulp`
- Run `./deploy.sh`
- `git push heroku master`


## Community

* Follow [@ionicframework on Twitter](https://twitter.com/ionicframework).
* Subscribe to the [Ionic Newsletter](http://ionicframework.com/subscribe/).
* Have a question that's not a feature request or bug report? [Discuss on the Ionic Forum](http://forum.ionicframework.com/).
* Read our [Blog](http://ionicframework.com/blog/).
* Have a feature request or find a bug? [Submit an issue](https://github.com/driftyco/ionic/issues).


## Authors

**Max Lynch**

+ <https://twitter.com/maxlynch>
+ <https://github.com/mlynch>

**Ben Sperry**

+ <https://twitter.com/benjsperry>
+ <https://github.com/bensperry>

**Adam Bradley**

+ <https://twitter.com/adamdbradley>
+ <https://github.com/adamdbradley>
