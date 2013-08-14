Request for Hack: Census Area API
====

Create a map data API for jurisdictions similar to or even forked from the code behind *boundaries.latimes.com*, a Django-driven LA-specific boundary API.

This is a simple NoGIS site for performing point-in-polygon checks on
individual lat/lon pairs via an API, suggested by the Team Las Vegas [Am I In
LV app](https://github.com/codeforamerica/amiinlv). This is a drastically slimmed-down version of [MySociety’s MapIt
application](http://code.mapit.mysociety.org/), with the important caveat that setup should be a
single-file, push-to-Heroku affair with only basic monitoring and display
beyond the REST API. This would be best delivered as a Python application
with an [open source GIS Heroku buildpack](https://github.com/migurski/heroku-buildpack-pygeo).
