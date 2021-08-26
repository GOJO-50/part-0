```sequence
browser -> server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/spa

server-->browser: HTML-code

browser->server: HTTP GEThttps://studies.cs.helsinki.fi/exampleapp/main.css

server-->browser: main.css

browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/spa.js

server-->browser: spa.js

browser->server: HTTP GEThttps://studies.cs.helsinki.fi/exampleapp/data.json

server-->browser: [{"content":"Mango","date":"2021-08-17T13:32:34.033Z"}, ...]
```

