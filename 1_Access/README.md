# Theme 1
Access to water supply and sanitation services and related health outcomes.  
Identify hotspots where basic access to water and sanitation is lacking 

### Proposed Methodology
1. Use the WorldPop raster data (1km grid), convert it to points at each relevant pixel.
2. Create a network graph from an OSM road network.
3. Use population point as origins and waterpoints as destinations
4. Run GOSTnets to calculate an Origin-Destination matrix of travel time between each origin-destination pair.

### Outputs
Map of travel time to nearest water point.
Summary statistics of % of population within 30 minutes, 1 hour, 2 hours of nearest water point.
More TBD based on feedback.