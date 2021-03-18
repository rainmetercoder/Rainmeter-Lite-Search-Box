# Rainmeter Lite Search Box
```
The code in the example is made for the Github search box. You can expand the searches by site.
```

# Requirements
[**Rainmeter**] (https://www.rainmeter.net/) - You can run versions 4.3.1 and higher.

# Installation
Download the file, upload it to the Rainmeter > Skins folder.

# Settings

>You can customize the Lite Search Box background.
```lua
[Background]
- ImageName=github.png
```

> Set the text to be displayed in the Lite Search Box.
```lua
[SearchLabel]
- Text=Search..
```

> Enter the URL of the web page you will search for in this section.
```lua
[SearchInput]
- Command1=!Execute ["https://github.com/search?q=$UserInput$"]
```
*Lite Search Box displays the results in whatever browser is your default browser.*

# Supported Search Inputs +200
Google, Yandex, Bing, Github, Facebook, Instagram, Twitter, TikTok, Medium, LinkedIn, Youtube, Vimeo, Pinterest, Tumblr, Snapchat, Reddit, Flickr, Swarm, Kik, Periscope, Tinder, Whatsapp, Telegram, Signal, Yahoo, Baidu, DuckDuckGo ... +200

# Screenshot 
![screenshot](https://user-images.githubusercontent.com/69988594/111701622-271c7300-884c-11eb-94a3-c8f8fc768e14.png)
