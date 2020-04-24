# CORS example

Follow the common [installation instructions](https://github.com/odino/wasec#installation). Then, run this example with nodejs, through `node index.js`.

You can then visit:

* [a GET request to sub.wasec.local that fails, because CORS is not enabled](http://wasec.local:7888/)
* [a GET request to sub.wasec.local which gos through, because CORS is enabled](http://wasec.local:7888/?cors=on)
* [a POST request to sub.wasec.local that requires a preflight request, which fails](http://wasec.local:7888/?method=POST)
