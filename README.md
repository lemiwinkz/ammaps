# Am Maps plugin for Craft CMS

## How does it look in the backend?

This plugin will add a new fieldtype called "Geo Mapper" that'll allow you to easily save addresses combined with the latitude and longitude.

![New field](resources/images/new-field.jpg "Geo Mapper")

Once you've added an address in the given fields and press the button to get the coordinates, Google Maps will be shown and a marker will display the location.

![Data in field](resources/images/data-in-field.jpg "Data in Geo Mapper field")

You can drag the marker around to update the coordinates to pinpoint the location exactly where you want.

![Drag the marker](resources/images/drag-for-coords.png "Drag the marker around in Geo Mapper field")

## How do I display the information on the frontend?

    {{ entry.GeoMapperFieldName.address }}
    {{ entry.GeoMapperFieldName.zip }}
    {{ entry.GeoMapperFieldName.city }}
    {{ entry.GeoMapperFieldName.country }}
    {{ entry.GeoMapperFieldName.lat }}
    {{ entry.GeoMapperFieldName.lng }}

## Contact

If you have any questions or suggestions, don't hesitate to contact us.

## Changelog

####1.0.1
-   Fields for the coordinates are now hidden.
-   The coordinates will be deleted automatically if none of the fields have data.
-   Google Maps will be shown if any of the fields has at least some data (e.g. : the address field).
-   Scrolling in Google Maps has been disabled.