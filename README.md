# Vessel Mapper

I built this page for mapping vessels whilst delivering a JavaScript course for the MetOffice back in 2018. It uses Leaflet for the map stuff and obtains data from MarineTraffic APIs. I wanted to show the delegates that they need not use complex frameworks/libraries like Angular or React to build small-scale apps like this. Note that tokens.js, the script in which the API tokens are declared, is not included for obvious reasons. 

You can see the page in action [here](https://optimistic-heyrovsky-02bfd1.netlify.app/vessel-mapper.html). Note that I've disabled editing of the num days field to limit the number hits to MarineTraffic (the API ain't free). This means that to see the vessel track you have to zoom in very close. 

Here are some vessel MMSI numbers you might use to test it out:
- 636022398: SA Europe (Oil Tanker)
- 205753000: Oceania (Floating Storage)
