# WebExpress
This is an advanced web browser created in C# WPF. 

# Features

* Colored tabs
* History
* Suggestions
* Downloads
* Incognito
* Screenshot function
* News
* Weather
* Settings
* Material Design UI
* Bookmarks
* Extensions

# Engine
This browser is using CefSharp. You can find it on: https://github.com/cefsharp/CefSharp

# Extensions
  Files structure
  Extensions
  * name.json
  * name.js
  * name.png
  
  name.json:
  ```
  {
    "id":"name",
    "description":"description",
    "logo":"name.png",
    "scripts": [
        {"file":"name.js"}
    ]
  }
  ```
  
  The extensions are loading to the `webview`. Code of extension is executing after page load event.

# Authors
This code was created by Eryk Rakowski (Sential)
