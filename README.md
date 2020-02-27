# Godot Community Map
This is a list of Godot regional communities, it is used as source data to generate the map in the [community page](https://godotengine.org/community). 

## Submitting your community

To add your community, create a pull request with a locations/region-name.cfg file. The file format is as follows:
```
Name: <The name of the community>
Country: <Country code in alpha-2 https://www.iban.com/country-codes>
[Coordinates: <Optional for cities, the coordinates on the map as latitude, longitude, like "23.5505° S, 46.6333° W" >]
Link: <Name>,<URL>
[Link: <Optional extra Link Name>,<Optional extra link Link URL>]
```

If your city or country exists, you can add PR extra links using the format above. Please check existing region name files to use as an example. If you want to obtain the coordinates for a place, try using Google Maps,OpenStreetMap or just search "Coordinates for <city>".


