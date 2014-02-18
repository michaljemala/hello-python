Sample Python Web application
=============================

The sample is using [Flask microframework](http://flask.pocoo.org/) and is intented to test the Python support on [Pivotal's Cloud Foundry](https://run.pivotal.io/).

Deploy to Cloud Foundry
-----------------------
```script
cf push <YOUR_APP_NAME> -m 128M -b https://github.com/heroku/heroku-buildpack-python.git
```
or
```script
cf push <YOUR_APP_NAME> -m 128M -b https://github.com/joshuamckenty/heroku-buildpack-python.git
```
or
```script
cf push <YOUR_APP_NAME> -m 128M -b https://github.com/ephoning/heroku-buildpack-python.git
````

Notes
-----
2014/02/18: The offical Heroku buildpack seems not to be working with Cloud Foundry.
