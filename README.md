# bootstrap-alert-jquery
Help for documentary snippet from (http://goo.gl/TGLccu | jQuery Script)

See **[demo website](http://www.jqueryscript.net/demo/jQuery-Plugin-To-Create-Animated-Bootstrap-Alerts-notify/)**

## How to Install?

### 1. Add Bootstrap CDN CSS & notify CSS:
```html
<link rel="stylesheet" href="http://netdna.bootstrapcdn.com/bootstrap/3.3.1/css/bootstrap.min.css">
<link href="notify.css" rel="stylesheet">
```

### 2. Add jQuery CDN JS & notify JS:
```html
<script src="//code.jquery.com/jquery-1.11.1.min.js"></script>
<script src="notify.js"></script>
```

### 3. Show a basic notification with default options.
```javascript
$.notify('I am a default notification box.');
```

### 4. Show a 'Success' notification.
```javascript
$.notify('I am a success box.', 'success');
```

### 5. All the default options.
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
