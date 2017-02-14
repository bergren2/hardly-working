# Hardly Working

## Development

To get the list of videos, I ran a query using [YouTube's Data API](https://developers.google.com/youtube/v3/docs/search/list).
Since the video series is no longer produced, I opted to just grab the results
from their API Explorer rather than set up a process to grab results. The
parameters I used were:

```json
{
  "part": "snippet",
  "channelId": "UCPDXXXJj9nax0fr0Wfc048g",
  "q": "allintitle:\"hardly working\""
}
```

## License

See LICENSE for details.
