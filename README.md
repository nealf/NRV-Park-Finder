# NRV Park Finder

What is this project?
------
Want to find a park or recreational area in the New River Valley? Want to find one that's close to you? How about finding the closest park with
tennis courts? Or tennis courts, a softball field, and a picnic shelter? The NRV Park Finder has (or will when it is done ;-) you covered! This
project is essentially a database of parks and recreational areas in the NRV with a mobile friendly website to query the data.

From a high-level architecture standpoint, we use OpenStreetMaps as our initial data source, which is then filtered and curated through a Google Sheet 
(so we can control what actually gets displayed as a 'park'), which is then put into our Postgres/PostGIS database, which is then served 
to the front-end client via a PostGraphQL endpoint.

Status
------
Currently a work in progress with no deployment

Contributing
------
Use Issues to join the discussion or come to a [hack night](http://www.meetup.com/CodeforNRV/)

Since our data is based on what's in [OpenStreetMaps](https://www.openstreetmap.org), you can help by adding or editing data there. 
Our [Google Sheet]() has a list of the parks we're including (open an issue if there's one that needs to be added or you'd like to 
be able to edit the sheet yourself).

License
------
The NRV Park Finder is licensed under the [MIT](LICENSE) license.