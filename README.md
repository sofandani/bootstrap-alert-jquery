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
<code>$.notify({</code>
 
<code>// custom notification message</code>
<code>message: "",</code>
 
<code>// 'default', 'info', 'error', 'warning', 'success'</code>
<code>status: "default",</code>
 
<code>// timeout in ms</code>
<code>timeout: 5000,</code>
 
<code>// 'top-center','top-right', 'bottom-right', 'bottom-center', 'bottom-left'</code>
<code>pos: 'top-center',</code>
 
<code>// z-index style for alert container</code>
<code>zIndex: 10400,
 
<code>// Function to call on alert close</code>
<code>onClose: function() {}</code>
 
<code>});</code>
