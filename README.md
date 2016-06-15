Why?
==

This is the *official* `analytics.js` with only the `Google Analytics` integration. I trimmed out the others with care line by line.

You should generate your own build from [analytics.js-core](https://github.com/segmentio/analytics.js-core) and its [integrations](https://github.com/segment-integrations/analytics.js-integration-google-analytics). This repo lives as a adhoc *standard* to compare to to test if your build works well.

Example
==

```javascript
var settings = {
  'Google Analytics': {
    trackingId: 'UA-XXXXXXX-XX',
  }
};

analytics.init(settings);

analytics.page();
```

[The original analytics.js README](https://github.com/segmentio/analytics.js/blob/master/Readme.md)
==
