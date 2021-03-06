# Interactive Layered Maps using Fusion Tables




<h3>Project:</h3>
Tasked with helping Austin Independent School District parents understand which community groups, vertical teams (i.e. middle school pertaining to elementary school) and board trustee zones apply to their children, these two custom Google Maps incorporate that data into a visualization.

<h3>Applications:</h3>

* [Google Fusion Tables](https://support.google.com/fusiontables/answer/2571232?hl=en)
  * Similar to Google Spreadsheets but with added capabilities. Emphasis on data visualization and manipulation. 
* [Google My Maps](https://www.google.com/maps/d/)
  * Allows you to make custom maps on the Google Maps platform. Map users can select which layers they want to view. Used for its integration with Google Fusion Tables, its user simplicity and its hosting capabilities, i.e. free, long-term and shareable.

<h3>Maps:</h3>

* [AISD Vertical Teams](http://aisd2.mgardiner.com)
  * Layers: ***High Schools***, ***Middle Schools***, ***Elementary Schools***, *North Austin Vertical Teams*, *Central Austin Vertical Teams*, *South Austin Vertical Teams*, *Special Campuses Vertical Team*, *Zipcodes*, *Community Registry – Tier 1*, *Community Registry – Tier 2*.
* [AISD Schools](http://aisd2.mgardiner.com)
  * Layers: ***High Schools***, ***Middle Schools***, ***Elementary Schools***, ***Trustee Member Districts***, *District Boundary*, *HS Attendance Boundaries*, *MS Attendance Boundaries*, *ES Attendance Boundaries*, *Zipcodes*.

<h3>Workflow:</h3>

* Find datasets that link location data to metadata (i.e. school zone boundaries to school names).
  * In this case, sourced from [Austin's Open Data Portal](https://data.austintexas.gov/).
  * Datasets: *Zipcodes*, *Board Trustee Zones*, *School Attendence Boundaries*, *Individual Campus Locations*, *District Vertical Teams* and *Applicable Community Groups*.
* Convert datasets to a format Fusion Tables can import.
  * KML is preferred but CSV, XLSX and GPX are permissible as well.
* Organize the data in Fusion Tables before creating seperate KML exports for each layer.
  * If a dataset already links location data to metadata, create a new Map view. If not, combine the two datasets by using Filters before creating a new Map view with the finished table.
* Once dataset has been imported into My Maps, color-code to differentiate between the data nodes.
  * School Layer: Elementary Schools - **Yellow**; Middle Schools - **Green**; High Schools - **Purple**.
  * Community Registry: Split into two layers: Groups covering **large** and **small** areas. Colar gradient differentiates within each layer.
  * Add or edit relevant metadata in My Maps (i.e. school board member names, contact information) by clicking *Open data table* in layer menu options.


<h3>Miscellaneous Data Sources:</h3>

* [Google Search](https://research.google.com/tables?corpus=fusion&hl=en&q=New+York)
  * Search tool linked above allows you to export web data into Fusion Tables (and also Google Spreadsheets).
  * "New York" used as an example query. Add the file format of what you're looking for.
* [GeoCommons](http://geocommons.com/)
  * Community sourced location-linked datasets.
* Major Cities
  * [Chicago](https://data.cityofchicago.org/)
  * [L.A.](https://data.lacity.org/)
  * [NYC](https://opendata.cityofnewyork.us/)

  
  
