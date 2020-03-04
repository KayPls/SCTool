# Social Club Tool
Modified by Kay. Special thanks to the original dev, Senexis.

## Functionality
This small tool provides you with some useful additional functionality Social Club itself does not yet offer:

- **Quick-add Users**: Allows you to send friend request to entered Social Club IDs instantly.
- **Delete All Friends**: Allows you to remove ALL friends instantly.
- **Reject All Friend Requests**: Allows you to reject ALL friend requests instantly.
- **Delete All Messages**: Allows you to remove ALL received and sent messages instantly.

## Usage
To use, add the following as the URL of a bookmark, then click it!

**Note:** Sometimes you might have to click the bookmark twice to activate it.

```
javascript:(function(){if(!document.getElementById("nt-mtjs")){var t=document.createElement("script");t.id="nt-mtjs",t.src="https://kaypls.github.io/SCTool/scm.min.js?"+(new Date).getTime(),document.getElementsByTagName("head")[0].appendChild(t)}setTimeout(function(){try{Init("",1)}catch(t){alert("Social Club Tool loading failed: Please try clicking your bookmark again.")}},1e3)})();
```
