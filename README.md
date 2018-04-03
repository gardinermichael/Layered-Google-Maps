# Interactive Layered Maps using Fusion Tables




<h3>Project:</h3>
Tasked with helping Austin Independent School District parents understand which community groups, vertical teams (i.e. which Middle School an Elementary school feeds into) and trustee zones apply to their children. 
<p>
 <br>
Created two custom Google Maps that incorporated that data into a visual display. Google My Maps was used for its integration with Google Fusion Tables, its user simplicity and its hosting capabilities, i.e. free and longterm.


<h3>Applications:</h3>

* [Google Fusion Tables](https://support.google.com/fusiontables/answer/2571232?hl=en)
  * Similar to Google Spreadsheets but with added capabilities. Emphasis on data visualization and manipulation. 
* [Google My Maps](https://www.google.com/maps/d/)
  * Allows you to make custom maps on the Google Maps platform. Map users can select which layers they want to view simultaneously.
  
<h3>Workflow:</h3>

* Find datasets that link location data to metadata (i.e. school zone boundaries to school names).
  * In this case, taken from [Austin's Open Data Portal](https://data.austintexas.gov/). Other cities: [Chicago](https://data.cityofchicago.org/), [L.A.](https://data.lacity.org/), [NYC](https://opendata.cityofnewyork.us/)
  * Datasets: *Zipcodes*, *Board Trustee Zones*, *School Attendence Boundaries*, *Individual Campus Locations*, *District Vertical Teams* and *Applicable Community Groups*.
* Convert datasets to a format Fusion Tables can import.
  * KML is preferred but CSV, XLSX and GPX are permissible as well.
* Organize the data in Fusion Tables before creating seperate KML exports for each layer.
  * If a dataset already links location data to metadata, create a new Map view.
  * If not, combine the two datasets by using Filters before creating a new Map view with the finished table.
* Once dataset has been imported into My Maps, color-code to differentiate between the data nodes.
  * School Layer: Elementary Schools - **Yellow**; Middle Schools - **Green**; High Schools - **Purple**.
  * Community Registry: Split into two layers: Groups covering **large** and **small** areas. Colar gradient differentiates within each layer.
  * Add relevant metadata if not previously linked in Fusion Tables (i.e. school board member names, contact information).


<h3>Data Sources:</h3>

* [Google Search](https://research.google.com/tables?corpus=fusion&hl=en&q=New+York)
  * Search tool linked above allows you to export web data into Fusion Tables (and also Google Spreadsheets).
  * "New York" used as example query. Add file formats and what you're looking for.
* [GeoCommons](http://geocommons.com/)
  * Community sourced location-linked datasets.

  
  
