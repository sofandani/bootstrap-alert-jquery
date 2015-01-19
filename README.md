# bootstrap-alert-jquery
Help for documentary snippet from (http://goo.gl/TGLccu | jQuery Script)

See Demo:
http://www.jqueryscript.net/demo/jQuery-Plugin-To-Create-Animated-Bootstrap-Alerts-notify/

# How to Install it:
<h4>Add Bootstrap CDN CSS & notify CSS:</h4>
<code><link rel="stylesheet" href="http://netdna.bootstrapcdn.com/bootstrap/3.3.1/css/bootstrap.min.css"></code>
<code><link href="notify.css" rel="stylesheet"></code>

<h4>Add jQuery CDN JS & notify JS:</h4>
<code><script src="//code.jquery.com/jquery-1.11.1.min.js"></script></code>
<code><script src="notify.js"></script></code>

#Show a basic notification with default options.
<code>$.notify('I am a default notification box.');</code>

#Show a 'Success' notification.
<code>$.notify('I am a success box.', 'success');</code>

#All the default options.
<code>
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
</code>
