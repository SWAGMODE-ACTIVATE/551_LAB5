# 551_LAB5

the temperature map webpage connects the user to their chosen mqtt topic and subscribes to it, and then allows the user to share their status, which creates a geojson object and publishes it to the topic. the javascript also contains functions to read new messages on the topic (ie the geojsons) and interpret them, creating leaflet map marker points that display the users locatoin and a random temperature value. the geolocation is taken from the web browser using javascript geolocation api. the user can only publish status when connected to the broker, and button to disconnect form it exists on the page as well.

Files-
pagestyle.css - this is the basic css stylesheet for page

index.html - webpage containining all of the html and javascript to work the page. also links to various external stylesheets like leaflet and mqtt paho.

.gitattributes - idk what this is but it looks important

readme.md- this file

ENGO 551 - Adv. Topics on Geospatial Technologies Nick Kennedy 30145355
