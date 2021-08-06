# Integration between OSM and authoritative data

This folder includes the materials produced within a research work carried out in 2021 by the Joint Research Centre (JRC) of the European Commission on investigating the enablers and barriers of OpenStreetMap integration with authoritative geospatial datasets from European national mapping agencies. The research work is lead by Alessandro Sarretta and Marco Minghini.

The folder contains some ETL processes and test data to reproduce an integration exercise.

In particular, it currently contains 3 ETL processes developed using the [QGIS graphical modeler](https://docs.qgis.org/3.16/en/docs/user_manual/processing/modeler.html) to combine address data in Finland and a test dataset of integrated addresses for the city of Helsinki.

The authoritative address dataset is provided by the National Land Survey (NLS) of Finland (https://www.maanmittauslaitos.fi/en) through an OGC API - Features service endpoint, accessed from the [New Address Information System](https://www.maanmittauslaitos.fi/osoitetietojarjestelma): https://beta-paikkatieto.maanmittauslaitos.fi/inspire-addresses/features/v1. The NLS address dataset is available under the [CC BY 4.0 license Creative Commons](https://creativecommons.org/licenses/by/4.0).

OpenStreetMap (OSM) data were extracted from the [Planet OSM](https://planet.openstreetmap.org), downloaded on 7 June 2021.

In the test dataset, the original data source is documented in the field "source", with the two values "OSM and "NLS".

Scientific outputs summarising the results of this work are currently in preparation and will be linked here once published.
