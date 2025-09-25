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
### Tecnologia Avanzada
![Tecnologia Avanzada](https://suministrosparalaindustria.com/wp-content/uploads/elementor/thumbs/utilidades-de-los-componeentes-electronicos-ql74zdvf3vfu5w4j2y1kx0sj1jxa7pqyk37o4m1rls.jpg)
### Chatgpt
![Chatgpt](https://kajabi-storefronts-production.kajabi-cdn.com/kajabi-storefronts-production/file-uploads/blogs/2147488964/images/a86eef2-748-3df7-ece5-e8a72dc1fc35_ChatGPT-Logo.jpg)
### Github
![Github](https://cdn.prod.website-files.com/5f5a53e153805db840dae2db/64e79ca5aff2fb7295bfddf9_github-que-es.jpg)
### Robot Avanzado
![Robot Avanzado](https://startupvalencia.org/wp-content/uploads/2024/02/tecnologia-2024-2.png)
