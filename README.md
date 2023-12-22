# AddisMapTransit-gtfs

Transit data of Addis Ababa, Ethiopia - based on OpenStreetMap

* Minibus data (Paratransit aka Informal Transport aka Popular Transport)
* Bus data
* Light rail

The open license for this data is currently not decided yet.

The data was collected on the ground and uploaded to OSM by AddisMap Team. This data is validated on OSM and directly extracted from the OSM OverPass API. 
Please use any GTFS validation tool of your preference to do GTFS Specific validation. Note that you need to check the OSM history and routes data status before extracting new GTFS data set as such changes on OSM would affect the GTFS data too.

The dataset is updated every night.

If you want to use this data please contact info@addismap.com

## Layout of the repository

The .txt files contain the extracted GTFS of all lines of the Addis Ababa Transport system.

Additionally there are the GTFS ZIP files ready to be used in your applications or for your analysis.

There are also the `generation.log` files with the output of OSM2GTFS to check for potential problems.

* [Download full GTFS](https://github.com/AddisMap/AddisMapTransit-gtfs-bus/blob/main/et-addisababa.zip)
* [Download only Minibus GTFS](https://github.com/AddisMap/AddisMapTransit-gtfs-bus/blob/main/et-addisababa-minibus.zip)
* [Download only Bus GTFS](https://github.com/AddisMap/AddisMapTransit-gtfs-bus/blob/main/et-addisababa-bus.zip)
* [Download only Anbessa Bus GTFS](https://github.com/AddisMap/AddisMapTransit-gtfs-bus/blob/main/et-addisababa-bus-ab.zip)
* [Download only Sheger Bus GTFS](https://github.com/AddisMap/AddisMapTransit-gtfs-bus/blob/main/et-addisababa-bus-sh.zip)

## See also

* https://addismaptransit.com/
* [Web Transit Planner](https://web.addismaptransit.com/)
