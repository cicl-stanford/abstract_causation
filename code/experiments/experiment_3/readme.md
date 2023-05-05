# Readme

To run the experiment, click on the `index.html` file and then change the ending of URL in the browser to one of the following: 

- index.html?condition=color_off
- index.html?condition=color_on
- index.html?condition=shape_off
- index.html?condition=shape_on

This part of the code in `index.html` reads the condition variable from the URL 

```
//get conditoin name (parse a URL parameter of the form experiment.html?condition=)
function get_url_param(name, defaultValue) { 
    var regexS = "[\?&]"+name+"=([^&#]*)"; 
    var regex = new RegExp(regexS); 
    var tmpURL = window.location.href; 
    var results = regex.exec(tmpURL); 
    if( results == null ) { 
        return defaultValue; 
    } else { 
        return results[1];    
    } 
}
```

