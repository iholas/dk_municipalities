# dk_municipalities
## Background
For a project, I needed to map municipalities in Denmark to their respective regions. This turned out to be a surprisingly difficult information to find a in a way that I could easily query and grab in a machine readable form - to use in my code. 

So, here are some files that should help showing this data in 2 different data structures. More datastructures may follow. 

Open to collaborate on this, and respond to requests to add more versions. 

## kommunerne.csv 
- A tall-form CSV
- Columns are 'Kommune', 'Region'
- In Danish (i.e., Copenhagen is København, and Regions are in Danish (e.g., Syddanmark instead of South Denmark ))
- Decode with "ISO-8859-1"

## kommunerne.json
- A JSON file 
- Structureis a simple dictionary where each municipality is a key and its region is its value 
- In Danish (i.e., Copenhagen is København, and Regions are in Danish (e.g., Syddanmark instead of South Denmark ))
- Reading with "UTF-8" decoder should work - let me know if not. 
