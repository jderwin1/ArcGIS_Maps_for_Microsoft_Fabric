This sample data is entirely fictional. It represents addresses, locations, and sales for 6,000 fictional customers in the United States, and locations of fictional stores. 

CustomerSales.csv field names:
"LOCATION_KEY" - Unique identifier
"CITY" - City name
"STATE_ABBR" - US State abbreviation
"STATE_NAME" - US State name
"ZIP_3" - first three digits of zip code
"ZIP" - five-digit zip code
"Address" - Street address
"LATITUDE" - WGS-84 Latitude in decmial degrees
"LONGITUDE" - WGS-84 Longitude in decmial degrees
"LATITUDE_WM" - Web Mercator Latitude
"LONGITUDE_WM" - Web Mercator Longitude
"Country" - Country
"SalesFY1" - Sales from fiscal year 1
"SalesFY2" - Sales from fiscal year 2

Stores.csv field names:
"FID" - Feature ID - Unique identifier	
"coords.x" - X coordinates in Albers Equal Area Projection (meters)
"coords.y" - Y coordinates in Albers Equal Area Projection (meters)
"Latitude" - WGS-84 Latitude in decmial degrees
"Longitude" - WGS-84 Longitude in decmial degrees
"SalesFY1" - Total sales from fiscal year 1 for all customers based on their closest store
"SalesFY2" - Total sales from fiscal year 2 for all customers based on their closest store	
"optional" - Binary operator (TRUE/FALSE)	
"SalesFY1_LTE150mi" - Total sales from fiscal year 1 for all customers within 150 miles based on their closest store

"SalesFY2_LTE150mi" - Total sales from fiscal year 1 for all customers within 150 miles based on their closest store
