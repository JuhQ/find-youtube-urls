# Get Youtube urls from string

## To use

```
var findYoutubeUrls = require("./index.js");

var string = "https://www.youtube.com/watch?v=gK87eRlyk7U";

var youtubeUrls = findYoutubeUrls(string);
// youtubeUrls = ["https://www.youtube.com/watch?v=gK87eRlyk7U"];
```


## Development

`npm install`

`gulp watch-test`


## Test
`gulp test`
