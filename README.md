# Vessel Mapper

I built this page for mapping vessels whilst delivering a JavaScript course for the MetOffice back in 2018. It uses Leaflet for the map stuff and obtains data from MarineTraffic APIs. I wanted to show the delegates that they need not use complex frameworks/libraries like Angular or React to build small-scale apps like this. Note that tokens.js, the script in which the API tokens are declared, is not included for obvious reasons. 

You can see the page in action [here](https://distracted-joliot-db68a1.netlify.app/). Note that I've disabled editing of the num days field to limit the number hits to MarineTraffic (the API ain't free). This means that to see the vessel track you have to zoom in very close. 

Here are some vessel MMSI numbers you might use to test it out:
- 310627000: Queens Mary II
- 311000084: Ramform Titan
- 311020600: Oasis of the Seas
