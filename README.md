# Operations Dashboard Utils

* [Refresh image](#refresh-image)
* [Show twitter timeline](#show-twitter-timeline)

## Refresh image

This project aims to help you to set up a simple HTML page that forces the browser to reload an image using URL parameters.

[Live demo](https://hhkaos.github.io/refresh-img//?url=http://turiscam.comunitatvalenciana.com/calp.jpg&interval=1000&width=700&collapsed=true)

### How this code works

Parameters:
* **url**: <string> image URL
* **interval**: <int> refresh rate (in ms) | default: 2000ms
* **width**: <int> image width in pixels | default: 100%
* **collapsed**: <any value> allows you to set body's margin and padding to 0px | default: false 

Sample page:

```
https://hhkaos.github.io/refresh-img//?url=http://turiscam.comunitatvalenciana.com/calp.jpg&interval=1000&width=700&collapsed=true
```


## Show twitter timeline

User timeline: [https://hhkaos.github.io/refresh-img/twitter.html?user=hhkaos](https://hhkaos.github.io/refresh-img/twitter.html?user=hhkaos)

User list: [https://hhkaos.github.io/refresh-img/twitter.html?user=hhkaos&list=innovation](https://hhkaos.github.io/refresh-img/twitter.html?user=hhkaos&list=innovation)

Check the [optional parameters](https://developer.twitter.com/en/docs/twitter-for-websites/timelines/guides/parameter-reference), example:
[https://hhkaos.github.io/refresh-img/twitter.html?user=hhkaos&list=innovation&theme=dark&collapsed=true&width=300](https://hhkaos.github.io/refresh-img/twitter.html?user=hhkaos&list=innovation&theme=dark&collapsed=true&width=300)

> Note: `collapsed`is not a twitter parameters, like in refresh image is to remove margins and paddings from the HTML
