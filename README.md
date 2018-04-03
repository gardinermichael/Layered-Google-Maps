# Layered-Google-Maps
Interactive layered Google Maps via Fusion Tables



<h3>Project:</h3>
Tasked with helping Austin Independent School District parents understand which community groups, vertical teams (i.e. which Middle School an Elementary school feeds into) and trustee zones apply to their children. Created two custom Google Maps that incorporated that data into a visual display.
<p>
Google My Maps was used for its integration with Google Fusion Tables, its user simplicity and its hosting capabilities (free and longterm).


<h3>Applications:</h3>

* [Google Fusion Tables](https://support.google.com/fusiontables/answer/2571232?hl=en)
  * Similar to Google Spreadsheets but with added capabilities. Emphasis on data visualization and manipulation. 

* [Google My Maps](https://www.google.com/maps/d/)
  * TK
  
<h3>Workflow:</h3>

* Find datasets that link location data to metadata (i.e. school zone boundaries to school names).
  * In this case, taken from [Austin's Open Data Portal](https://data.austintexas.gov/).
  * Datasets: *Zipcodes*, *Board Trustee Zones*, *School Attendence Boundaries*, *Individual Campus Locations*, *District Vertical Teams* and *Applicable Community Groups*.
* Convert datasets to a format Fusion Tables can import.
  * KML is preferred but CSV, XLSX and GPX are permissible as well.
* Organize the data in Fusion Tables before creating seperate KML exports for each layer.
  * Users will be able to select which layers they want to view simultaneously in My Maps.
* Once dataset has been imported into My Maps, color-code to differentiate between the data nodes.
  * School Layer: Elementary Schools - **Yellow**, Middle Schools - **Green**, High Schools - **Purple**.
  * Community Registry: Split groups covering Large and Small areas into two layers. Colar gradient differentiates within layer.
  * Add relevant metadata if not linked in Fusion Tables (i.e. school board member names, contact information).
