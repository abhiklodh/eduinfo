#EduInfo
Edu Info is a website which determines where a user should go for lunch. The site utilises HTML5 to draw a wheel of a collection of local restaurants which is obtained from a custom RESTful API and Google Places.

[Click here to view demo.](http://abhiklodh.github.io/eduinfo)

##Features

* Range finder to determine a suitable distance to search for the initial 12 places.
* Get location via Google Maps or by current location.
* Variable search parameters.
* View selected place on Google Maps.
* View rating out of 5 for selected place
* Spin the wheel using click-and-drag or spin button
* Location search net increments when few results are found (for rural areas).
* Search for "restuaraunts", "food" or "bar".
* Shareable url links (allows others to view the same results).

##Search Radius
When a user is in a rural area and the wheel can not find a suitable number of places within the default search radius, the search will increment until a suitable number is found.

![Search radius increments](http://i.imgur.com/8YYuZlg.png "Search radius increments")

Increment | Search Radius 
--- | ---
1 | 300
2 | 400
3 | 500
4 | 1000
5 | 1500
6 | 2000
7 | 2500
8 | 3000

##Resources:

* [Creating a roulette wheel using HTML5.](http://tech.pro/tutorial/1008/creating-a-roulette-wheel-using-html5-canvas)
* [HTML5 confetti.](http://codepen.io/linrock/pen/Amdhr)

