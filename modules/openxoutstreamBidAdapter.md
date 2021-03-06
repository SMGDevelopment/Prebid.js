# Overview

```
Module Name: OpenX Outstream Bidder Adapter
Module Type: Bidder Adapter
Maintainer: opensource@yieldmo.com, jimmy.tu@openx.com
Note: Ads will only render in mobile
```

# Description

Module that connects to OpenX's demand sources for outstream to Yieldmo.

This bid adapter supports Banner.

Note that the only supported size for demand is currently 400 x 300.

# Example
```javascript
var adUnits = [
  {
    code: 'test-div',
    mediaTypes: {
      'banner': {
        sizes: [[400, 300],  // a display size
      }
    },
    bids: [
      {
        bidder: 'openxoutstream',
        params: {
          unit: '540141567',
          delDomain: 'se-demo-d.openx.net',
        }
      }
    ]
  }
];
```

# Additional Details
[Banner Ads](https://docs.openx.com/Content/developers/containers/prebid-adapter.html)

