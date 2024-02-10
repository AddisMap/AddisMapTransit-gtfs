# AddisMapTransit-gtfs

Transit data of Addis Ababa, Ethiopia - based on OpenStreetMap

* Minibus data (Paratransit aka Informal Transport aka Popular Transport)
* Bus data
* Light rail

The data is under the OSM License (ODbL).

## Sponsors

Sponsored for a one year term under the [DigitalTransport 4 Africa Innovation Challenge](https://digitaltransport4africa.org/innovation-challenge/) by [WRI](https://wri.org), [AFD FR](https://www.afd.fr/en) - partners:

![DT4A Sponsors](https://addismaptransit.com/wp-content/uploads/sites/6/2022/11/sponsors.png)

Much of the data was collected on the ground and uploaded to OSM by AddisMap Team that was made possible through the [DT4A Innovation Challenge Grant Award](https://digitaltransport4africa.org/wri-and-partners-select-4-winners-for-digital-transport-for-africa-innovation-challenge-2/) that was organized by [DT4A](https://digitaltransport4africa.org/) on December 7, 2021. This data is validated on OSM and directly extracted from the OSM OverPass API. 
Please use any GTFS validation tool of your preference to do GTFS Specific validation. If you prefer pre-validated GTFS dataset you can checkout the [DT4A GitLab repository here](https://gitlab.com/digitaltransport/data/africa/addis-ababa). Note that you need to check the OSM history and routes data status before extracting new GTFS data set as such changes on OSM would affect the GTFS data too.

The dataset is updated every night from OpenStreetMap data.

If you want to use this data please contact info@addismap.com

## Layout of the repository

The .txt files contain the extracted GTFS of all lines of the Addis Ababa Transport system.

Additionally there are the GTFS ZIP files ready to be used in your applications or for your analysis.

There are also the `generation.log` files with the output of OSM2GTFS to check for potential problems.

* [Download full GTFS](https://github.com/AddisMap/AddisMapTransit-gtfs/raw/main/et-addisababa.zip)
* [Download only Minibus GTFS](https://github.com/AddisMap/AddisMapTransit-gtfs/raw/main/et-addisababa-minibus.zip)
* [Download only Bus GTFS](https://github.com/AddisMap/AddisMapTransit-gtfs/raw/main/et-addisababa-bus.zip)
* [Download only Anbessa Bus GTFS](https://github.com/AddisMap/AddisMapTransit-gtfs/raw/main/et-addisababa-bus-ab.zip)
* [Download only Sheger Bus GTFS](https://github.com/AddisMap/AddisMapTransit-gtfs/raw/main/et-addisababa-bus-sh.zip)

## See also

* https://addismaptransit.com/
* [Web Transit Planner](https://web.addismaptransit.com/)
