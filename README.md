# Using-the-JSON-extractor
going to *System* -> *Input* and clicking on the Manage extractors button
Next, you need to load a message to extract data from, and select the field containing the JSON document.
The following page let you add some extra information to tell Graylog how it should extract the information. Let’s illustrate how a message would be extracted with an example message:
## message
```
thinkpad nginx: { "timestamp": "2019-09-07T13:46:01+04:30", "remote_addr": "192.168.43.174", "body_bytes_sent": 0, "request_time": 0.000, "response_status": 304, "request": "GET / HTTP/1.1", "request_method": "GET", "host": "192.168.43.174","upstream_cache_status": "","upstream_addr": "","http_x_forwarded_for": "","http_referrer": "", "http_user_agent": "Mozilla/5.0 (X11; Ubuntu; Linux x86_64; rv:69.0) Gecko/20100101 Firefox/69.0" }
```
## Add extractor

System -> Input -> Manage Extractor -> Get started -> Load Massage 
## 1. Extract data from message into json
(select massage)
![massage](https://user-images.githubusercontent.com/36330171/64477089-a25b8e00-d1ac-11e9-9c6e-e1fc12b99e99.jpg)
## 2. Extract data from json into
![jason](https://user-images.githubusercontent.com/36330171/64478138-1d2aa600-d1b9-11e9-82a4-4a07c15c27dc.jpg)

