# Introduction

[OpenData.sk initiative](http://opendata.sk) is, as part of our activities, among other things
trying to help with publishing and usage of Open Data. For that, we're showing here how to:

1. maintain a copy of a CSV dataset in PostgreSQL database with [harvester](https://gitlab.com/soit/korona.gov.sk.csv-harvester)
2. create a simple visualization of a CSV data with plotly.js: https://hanecak.github.io/viz-covid_19-sk/

Suggestions, bug-reports and pull-request are welcome is the [issue tracker](https://github.com/hanecak/viz-covid_19-sk/issues).
 
# License

MIT License, see [LICENSE](LICENSE) for more details.

## 3rd party components

- [plotly.js](https://plot.ly/javascript/) (MIT)

# TODO

- selected categories to be taken from URI, to allow deep-linking and sharing of custom selections
- ...

# DEV tips

- loading of CSV requires HTTP, you can setup a primitive server by running `python -m http.server`
in the directory with this project
