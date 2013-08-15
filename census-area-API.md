Request for Hack: Census Area API
========

Create a map data API for jurisdictions similar to or even forked from the code behind [boundaries.latimes.com](http://boundaries.latimes.com), a Django-driven LA-specific boundary API.


The Product
--------

This is a simple NoGIS site for performing point-in-polygon checks on
individual lat/lon pairs via an API, similar to Team Las Vegas [Am I In
LV app](https://github.com/codeforamerica/amiinlv). This is also a drastically slimmed-down version of [MySociety’s MapIt
application](http://code.mapit.mysociety.org/), with the important caveat that setup should be a
single-file, push-to-Heroku affair with only basic monitoring and display
beyond the REST API. This would be best delivered as a Python application
with an [open source GIS Heroku buildpack](https://github.com/migurski/heroku-buildpack-pygeo).

Services offered by the API:

* GeoJSON responses and simple GET requests.
* Search for areas by [US Census FIPS codes](http://quickfacts.census.gov/qfd/meta/long_fips.htm), e.g. `FIPS=0653000`.
* Search for areas geographically by tile or bounding box, e.g. `where=tile:12/656/1582` or `where=bbox:37.7881,-122.3437,37.8575,-122.2559`.

Nice to have:

* [UTFGrid format](https://github.com/mapbox/utfgrid-spec/blob/master/1.3/utfgrid.md) responses for tile searches.
* Optional geography in responses for size.
* Paged respnses.


Help Available
--------

[Michal Migurski](mailto:mike@codeforamerica.org) and [Sophia Parafina](https://github.com/spara) are 2013’s GIS experts at CfA.


How To Start
--------

Check out the [open source GIS Heroku buildpack](https://github.com/migurski/heroku-buildpack-pygeo), and write a simple *Hello World* [Flask](http://flask.pocoo.org) application using it.