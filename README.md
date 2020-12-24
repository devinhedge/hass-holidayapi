[![GitHub Activity][commits-shield]][commits]
[![License][license-shield]](LICENSE)

# hass-holidayapi

_Home Assistant Component to integrate with [WattBox][https://holidayapi.com/]._

Easiest way to install this component is through [HACS][hacs].

Configuration through `configuration.yaml`, not available in UI yet.

Example Config:
```
holidayapi:
- developerapi_KEY: '_YOUR_API_KEY_' # Get your Developer API KEY at the Holiday API website
  
```

This implements the [Holiday API in python][pythonapi]

##Configuration Options:

* *developerapi_KEY*: Your API Key from [Holiday API](https://holidayapi.com/signup) (Required)

## API Resources for calling the API

## Required:
* 'country': 'US',
* 'year':    2016,

## Optional:
    # 'month':    7,
    # 'day':      4,
    # 'previous': True,
    # 'upcoming': True,
    # 'public':   True,
    # 'pretty':   True,


<!---->

***


[hacs]: https://hacs.xyz/
[forum]: https://community.home-assistant.io/
[hacs]: https://github.com/custom-components/hacs
[pythonapi]: https://github.com/holidayapi/holidayapi-python
