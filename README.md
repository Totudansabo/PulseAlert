# PulseAlert MVP

An installable mobile web prototype for PulseAlert, a Nigeria focused health education application. This version includes a home feed, topic search and filters, saved guides, location preference, and offline access after first load. Health guides link to WHO source pages. No live alerts or push notifications are issued.

## Run locally

```sh
cd pulsealert
python3 -m http.server 8080
```

Open http://localhost:8080. Installability and service worker caching require HTTPS or localhost. On Android Chrome, use **Add to Home screen** after opening an HTTPS hosted version.

## Next production milestones

1. Set up a reviewed content workflow and publisher roles in an admin panel.
2. Integrate authenticated, location targeted alert publishing with source, timestamp, expiration, review, and correction history.
3. Build Android/iOS clients and push notifications once the alert workflow is approved.
4. Conduct clinical review, accessibility testing, privacy design, and local pilot before a public launch.
