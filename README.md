# iframefader
iframefader provides simple crossfading slideshow functionality for a selection of webpages.

Ideal for a raspberry pi with chrome browser in kiosk mode! No dependences, uses CSS3 animation for smooth fade transitions.

Use the json file to set which urls you want to display, the animation speed and an optional ip address to be overlayed at the bottom corner of the screen. 


#json settings
```
var settings = {
	"pages":[
				{"page":"http://www.hypermodernism.com/"},
				{"page":"http://www.hypermodernism.com/cv/"},
				{"page":"http://www.hypermags.com"},
				{"page":"http://www.bbc.com"}
			],
 	"animationSpeed":10,
 	"ipInfo":"My Message here......??"
}
```
