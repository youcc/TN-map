Make a TN map on Ubuntu16.04.1 using D3 and TopoJSON by following [Mike Bostock's Merged Choropleth](https://bl.ocks.org/mbostock/670b9fe0577a29c39a1803f59c628769). This project use topomerge to combine census tracts in the same density interval.

### Create the following files in local 
index.html # changed height to 700    
package.json  # changed a few devDependencies to make "npm install" work   
prepublish # changed FIPS code from 06 (CA) to 47 (TN), height 700 

### Convert data by running "npm install" on package.json
```sh
$ npm install 
```  
### Load the fillowing files to local server or remote server
index.html  
topo.json  
  
### Open index.html in your server to see the map 
