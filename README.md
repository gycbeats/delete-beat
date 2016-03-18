**Clears drum patterns on [html5drummachine](http://html5drummachine.com)**

Use [here](http://gycbeats.github.io/delete-beat) or copy & paste into the URL field of a new bookmark:
```
javascript:(function(){
    if (confirm("Are you sure you want to delete your beat?")){localStorage.drums=[];window.location="http://html5drummachine.com";}
}());
```