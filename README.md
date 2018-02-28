# Layered-Google-Maps
Interactive layered Google Maps via Fusion Tables



<h3>Project:</h3>
Tasked with helping Austin Independent School District parents understand which community groups, vertical teams (i.e. which Middle School does an Elementary school TK) and trustee zones apply to their children, two custom Google Maps were created that incorporated that data into a visual display.

Google My Maps was used for its integration with Google Fusion Tables, its user simplicity and its hosting capabilities (free and longterm).


<h3>Applications:</h3>

* [Google Fusion Tables](https://support.google.com/fusiontables/answer/2571232?hl=en)
  * TK

* [Google My Maps](https://www.google.com/maps/d/)
  * TK
  
<h3>Workflow:</h3>

* Combine the relevant datasets via Fusion Tables using the location data
  * In this case, taken from [Austin's Open Data Portal](https://data.austintexas.gov/).
  * Combined: *Zipcodes*, *Board Trustee Zones*, *School Attendence Boundaries*, *Individual Campus Locations*, *District Vertical Teams* and *Applicable Community Groups*.
* Color-code to differentiate between the data nodes TK
  * Elementary Schools: Yellow, Middle Schools: Green, High Schools: Purple
  * Seperate layers and let user select which ones they want to view in conjunction with others
  
* Convert the location data in to a format that Google will import Fusion Tables.
  * KML is preferred but CSV, XLSX and GPX are permissible as well.
* Add relevant metadata (School board member descriptions, contact information
  * TK
