# Blush
Blush is a minimal startpage that changes the featured image and quote with every refresh and is convenient to leave open with a weather and automatically updating time feature.

![alt text](https://github.com/chloechantelle/blush/blob/master/previews/Blush%20V3.png "Blush Preview")

# Instructions
<h3>Firefox</h3>

*Homepage*
    
Ctrl+L > about:preferences > Home Page > Enter the HTML file location.
        
*New tab*
    
Install the <a href="https://addons.mozilla.org/en-US/firefox/addon/new-tab-override" target="_blank">New Tab Override</a> extension > Ctrl+Shift+A > Extensions > New Tab Options > Enter the HTML file location.

<h3>Chrome</h3>

*Homepage*

Settings > Show Home Button > Change New Tab > Enter the HTML file location.

*New tab*

Install the <a target="_blank" href="https://chrome.google.com/webstore/detail/new-tab-redirect/icpgjfneehieebagbmdbhnlpiopdcmna?hl=en">New Tab Redirect</a> extension > Settings > More Tools > Options for New Tab Redirect > Enter the HTML file location.

# Customizing

<h3>Images</h3>

Change the names of the images in the `randomImage` array and move the new images to the `img folder`.

`var images = ['img/1.jpg', 'img/2.jpg', 'img/3.jpg', 'img/4.jpg', 'img/5.jpg', 'img/6.jpg', 'img/7.jpg', 'img/8.jpg'];`

Make sure the images are around the same size (500x500).

<h3>Quotes</h3>

Change the quotes in the `quotes[0]` variables

`quotes[2] = "God damn I love paper like I'm Michael Scott.";`

You can even remove or add more if you'd like!

<h3>Weather</h3>

Change the `json_url` API url, only change the weather ID number to your area's ID.

`var json_url = "http://api.openweathermap.org/data/2.5/weather?id=**7839562**&appid=832719dabc0aaac91c4a93c2a64e12d4&units=metric";`

<a target="_blank" href="https://openweathermap.org">Find your location ID on openweathermap.com</a>

<h3>Colors/Fonts</h3>

Colors and fonts are set in the `:root` variables at the top of the `style.css` file.

# Disclaimer

All images found on Tumblr.

# Issues
<a href="https://github.com/chloechantelle/blush/issues/new">Submit an issue</a> if you have any problems.
