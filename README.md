# OBS clock

# Usage
A script for OBS Studio (https://obsproject.com/) to embed a current date and timestamp. No other softwares and plugins are needed. Just OBS Studio and the built-in Browser Source input.

# Examples
Vanilla
https://cdn.rawgit.com/sam0737/a0ee8ca253fc5c84b2aa2ac018f7b8ad/raw/108196e17c2c9d79ff60ed3bf788973ab94da9af/clock.html

White text
https://cdn.rawgit.com/sam0737/a0ee8ca253fc5c84b2aa2ac018f7b8ad/raw/108196e17c2c9d79ff60ed3bf788973ab94da9af/clock.html?style=font: bold 30px monospace; color: white;

Rounded rectangle
https://cdn.rawgit.com/sam0737/a0ee8ca253fc5c84b2aa2ac018f7b8ad/raw/108196e17c2c9d79ff60ed3bf788973ab94da9af/clock.html?style=font: bold 30px monospace; color: lightgray; display: inline-block; border-radius: 5px; padding: 2px 5px; background-color: rgba(0, 0, 0, 0.5);

With US date formatting
https://cdn.rawgit.com/sam0737/a0ee8ca253fc5c84b2aa2ac018f7b8ad/raw/108196e17c2c9d79ff60ed3bf788973ab94da9af/clock.html?style=font: bold 30px monospace; color: lightgray; display: inline-block; border-radius: 5px; padding: 2px 5px; background-color: rgba(0, 0, 0, 0.5)&format=MMM DD YYYY HH:mm:ss;

# Parameters
Use style to add more style to the output element
While bodyStyle for the style to the body element
Use format to control the date format. For the syntax, see https://momentjs.com/docs/#/displaying/format/

# Date
?style=font:%20bold%2050px%20monospace;%20color:%20rgba(179,255,179,1);%20border-radius:%205px;%20padding:%202px%205px;background-color:%20rgba(0,0,0,0.8);%20margin:%20auto;%20width:%20320px;%20text-align:%20center%20&format=DD/MM/YYYY

# Time
?style=font:%20bold%2050px%20monospace;%20color:%20rgba(255,255,0,1);%20border-radius:%205px;%20padding:%202px%205px;background-color:%20rgba(0,0,0,0.8);%20margin:%20auto;%20width:%20250px;%20text-align:%20center%20&format=kk:mm:ss
