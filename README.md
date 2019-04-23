# URL Grabber

Just a simple page that grabs the URL suffix (lets user type in key-value pairs in the URL). The Content needs to be appended to the `/index.html` starting with a `?`. Also each key is seperated from its value by `=` and each key-value pair is seperated by `;` (semicolons). The URL-suffix needs to be structured as follows: `KEY=VALUE;KEY2=VALUE2`, whereas `KEY` is text (string) and `VALUE` is a number. For example:
- https://dcts.github.io/URL-grabber/index.html?Key1=10;Key2=3000;
- https://dcts.github.io/URL-grabber/index.html?Key1=10;
- https://dcts.github.io/URL-grabber/index.html?Key1=10012;Key2=39000;Key3=50;

