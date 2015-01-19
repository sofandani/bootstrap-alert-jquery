# bootstrap-alert-jquery
Help for documentary snippet from (http://goo.gl/TGLccu | jQuery Script)

See Demo:
http://www.jqueryscript.net/demo/jQuery-Plugin-To-Create-Animated-Bootstrap-Alerts-notify/

# How to Install it:
<h4>Add Bootstrap CDN CSS & notify CSS:</h4>
> <link rel="stylesheet" href="http://netdna.bootstrapcdn.com/bootstrap/3.3.1/css/bootstrap.min.css">
> <link href="notify.css" rel="stylesheet">

<h4>Add jQuery CDN JS & notify JS:</h4>
> <script src="//code.jquery.com/jquery-1.11.1.min.js"></script>
> <script src="notify.js"></script>

<h4>Show a basic notification with default options.</h4>
```javascript
$.notify('I am a default notification box.');</code>
```

<h4>Show a 'Success' notification.</h4>
```javascript
$.notify('I am a success box.', 'success');
```

<h4>All the default options.</h4>
```javascript
$.notify({
 
// custom notification message
message: "",
 
// 'default', 'info', 'error', 'warning', 'success'
status: "default",
 
// timeout in ms
timeout: 5000,
 
// 'top-center','top-right', 'bottom-right', 'bottom-center', 'bottom-left'
pos: 'top-center',
 
// z-index style for alert container
zIndex: 10400,
 
// Function to call on alert close
onClose: function() {}
 
});
```
