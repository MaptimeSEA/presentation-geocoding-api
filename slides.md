## Welcome to MaptimeSEA!

introduce yourself to your neighbor

*install* a **text editor**

big thanks to our wonderful hosts, **Broad Street Maps** and **WeWork Seattle**



## Geocoding & APIs

### MaptimeSEA
3/4/2015

_Welcome!_<!-- .element: class="fragment" data-fragment-index="1" -->



## Why geocode?
_you have an address, but want coordinates_<!-- .element: class="fragment" data-fragment-index="1" -->



## Geocoding has been around
_where do we geocode?_ <!-- .element: class="fragment" data-fragment-index="0" -->

_desktop GIS much?_ <!-- .element: class="fragment" data-fragment-index="1" -->


Why might the **desktop** approach be problematic for the **web**?



## So what is
# API?
_Application Programming Interface_ <!-- .element: class="fragment" data-fragment-index="0" -->


### But what do they actually do?
_they provide a means of communication on the web_ <!-- .element: class="fragment" data-fragment-index="0" -->

_in our case, an API allows us to send a query, and get back data that matches that query_ <!-- .element: class="fragment" data-fragment-index="1" -->


let's look at an example



`http://api.example.com?query=hello&format=json`
_break it down_ <!-- .element: class="fragment" data-fragment-index="0" -->


`http://api.example.com?query=hello&format=json`

**api.example.com** is where we find the API


`http://api.example.com?query=hello&format=json`

**?** indicates parameters will follow

_this is just a convention of communication on the web_ <!-- .element: class="fragment" data-fragment-index="0" -->


`http://api.example.com?query=hello&format=json`

**query=hello** is a parameter, `query` which for this request, equals `hello`


`http://api.example.com?query=hello&format=json`

**&** delimits parameters


`http://api.example.com?query=hello&format=json`

**format=json** is another parameter, that basically says, "hey send me some json!"



## Build it

http://maptimesea.github.io/2015/03/03/gecoding-api.html
