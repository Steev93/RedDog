Territory map
====
[Live page](https://steev93.github.io/RedDog/)
This interactive (Google) map shows you the location of current Red Dog territory/gang zones.

## How to submit new locations
1. Right click on the map to add points.
2. Click "Add New Region" to print out the region data.
3. Replace "\<edit this\>" with correct information.
4. Replace the id with an unused id while trying to maintain the pattern in `locations.json`
5. Change the type, add a video or images, and change the color of the region.
6. Add new region to `locations.json` and create a pull request.

Example:
		
		"type": "Type of Location",
		"title": "Name of Location",
		"notes": "Notes about this Location",
		"order": 0,
		"strokecolor": "4E5B31",
		"fillcolor": "00000000",
		"latlngarray": [
			{"lat": -56.469, "lng": -16.248},
			{"lat": -56.469, "lng": 2.537},
			{"lat": -59.169, "lng": 2.537},
			{"lat": -59.169, "lng": -0.894},
			{"lat": -59.909, "lng": -0.894},
			{"lat": -59.909, "lng": -3.584},
			{"lat": -60.141, "lng": -3.584},
			{"lat": -60.141, "lng": -16.248}

## License

[WTFPL](LICENSE)

## Version

1.1.0

## Credits

To [danharper](https://github.com/danharper/) for [his work](https://github.com/danharper/GTAV) on the GTA V map.
To [gta5-map](https://github.com/gta5-map) for [their work](https://github.com/gta5-map/gta5-map.github.io) on the GTA V map.

## Star History

By starring this repository you attract contributors to invest time into maintaing it.

[![Star History Chart](https://api.star-history.com/svg?repos=skyrossm/np-gangmap&type=Date)](https://star-history.com/#skyrossm/np-gangmap)
