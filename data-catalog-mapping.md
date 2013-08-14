Request for Hack: Map Open Data Catalogs
========

Most open government data portals such as those provided by [CKAN](http://ckan.org) or [Socrata](http://socrata.com) are local to a given jurisdiction, such as a city or county. Most such jurisdictions can also be mapped to unambiguous spatial identifiers, such as [Open Civic Data ID’s](https://github.com/opencivicdata/ocd-division-ids) and [US Census FIPS codes](http://quickfacts.census.gov/qfd/meta/long_fips.htm).

We are interested in a mapping of open data catalogs (not data sets!) to FIPS and OCD ID’s. For example, the city of Oakland has FIPS number [0653000](http://quickfacts.census.gov/qfd/states/06/0653000.html) and OCD ID [ocd-division/country:us/state:ca/place:oakland](https://github.com/opencivicdata/ocd-division-ids/blob/080131a4c8cf/identifiers/country-us/state-ca-census.csv#L348), maintains an open data catalog at [data.oaklandnet.com](https://data.oaklandnet.com) and benefits from an additional community-supported catalog at [data.openoakland.org](http://data.openoakland.org).


The Product
--------

This is primarily a research project, and we are looking for a simple database or spreadsheet mapping URLs and identifiers, such as this partial sample for the Oakland example given above:

    Name    URL                         FIPS    OCD
    Oakland https://data.oaklandnet.com 0653000 ocd-division/country:us/state:ca/place:oakland
    Oakland http://data.openoakland.org 0653000 ocd-division/country:us/state:ca/place:oakland


Help Available
--------

Ask [Michal Migurski](mailto:mike@codeforamerica.org) about Census identifiers and how to find them. Contact the maintainers of [ocd-division-ids](https://github.com/opencivicdata/ocd-division-ids) for clarification on OCD IDs.


How To Start
--------

Starting points for data catalogs:

* [http://ckan.org/instances/](http://ckan.org/instances/)
* [https://opendata.socrata.com/browse?tags=socrata+customers](https://opendata.socrata.com/browse?tags=socrata+customers)

A Google spreadsheet or text file in Git would be an appropriate start to this project.