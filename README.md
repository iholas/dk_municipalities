# dk_municipalities
For a project, I needed to map municipalities in Denmark to their respective regions. This turned out to be a surprisingly difficult information to find a in a way that I could easily query and grab in a machine readable form - to use in my code. 

So, here is a CSV with the municipalities in Danish. Other data formats may show up later. 

Open to collaborate on this, and respond to requests to add more versions. 

## kommunerne.csv 
- Municipalities and regions in Danish (i.e. Copenhagen is København)
- Columns are 'Kommune', 'Region'
- Decode with "ISO-8859-1"

## kommunerne.json
- A JSON file 
- Structureis a simple dictionary where each municipality is a key and its region is its value 
- Municipality names are in Danish (Copenhagen is København)
- Values were made ASCII compatible
- Reading with "UTF-8" decoder should work - let me know if not. 
