# HSTS example

Run this example with nodejs, through `node index.js`..

You can then visit:

* [a malicious win-a-hummer website that uses clickjacking to steal all your money from another URL! (no worries, it's safe to click links in the example :))](https://localhost:7888/)
* [the same attack, prevented through X-Frame-Options](https://localhost:7888/?xfo=on)
* [the same attack, prevented through Content Security Policy](https://localhost:7888/?csp=on)