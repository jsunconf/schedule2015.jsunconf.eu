# schedule2015.jsunconf.eu

## Howto update schedule
The fastest way from zero to an updated online schedule.

* [Install the cosch gem](https://rubygems.org/gems/cosch)
* Create your new schedule `cosch new DIR`
* Edit `schedule.yml` to fit your needs (Push your changes, if you like)
* Deploy to Github Pages: `cosch deploy`
  * to check changes before you deploy, do a `cosch build` and serve the build/ folder e.g. using php `php -S localhost:8090` or python `python -m SimpleHTTPServer 8090` 
* **Done**
