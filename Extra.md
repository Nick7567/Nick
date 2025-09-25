```javascript


function showtime () {
var now = new Date();
var hours = now.getHours();
var minutes = now.getMinutes();
var seconds = now.getSeconds()
var timeValue = "" + ((hours >12) ? hours -12 :hours)
timeValue += ((minutes < 10) ? ":0" : ":") + minutes
timeValue += ((seconds < 10) ? ":0" : ":") + seconds
timeValue += (hours >= 12) ? " P.M." : " A.M."
document.clock.face.value = timeValue;
// you could replace the above with this
// and have a clock on the status bar:
// window.status = timeValue;
timerID = setTimeout("showtime()",1000);
timerRunning = true;
}
```
![Tecnologia Avanzada](https://suministrosparalaindustria.com/wp-content/uploads/elementor/thumbs/utilidades-de-los-componeentes-electronicos-ql74zdvf3vfu5w4j2y1kx0sj1jxa7pqyk37o4m1rls.jpg)
