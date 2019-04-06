# API Documentation

## Todo:

- [ ] Investiate other API documentation methods
- [ ] Fully enumerate api tree
- [ ] Fill in API
- [ ] Have coffee

## Draft API

### /ui/

A general user interface. Perhaps made with bootstrap and JS to access the rest of the controls?

### /grafana/

A redirection URL to the grafana port and page. 

### /influx/

A redirection URL to the influxDB instance.

### /controller/{name}

**GET**: Get general json of controller status.

### /controller/{name}/sensors/

**GET**: Get all sensors from specific controller.

### /controller/{name}/sensor/{name}/

### /controller/{name}/RTC/

### /controller/{name}/outlet/{id}

`id` is 0-5 for the given outlet

**GET**: Get current value

**POST**: Set new value

**PUT**: Set new value

**DELETE**: Shortcut to set value to 0



