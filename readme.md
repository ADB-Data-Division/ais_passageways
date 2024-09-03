This repository is a supplement to "Analyzing Anomalous Events in Passageways with High-Frequency Ship Signals".

It contains [notebooks](notebooks) and [data outputs](data) from the algorithms to capture transits 
in passageways and re-routes using Automatic Identification System (AIS) 
data. The transits algorithm are applied to 
[Suez Canal](notebooks/Suez Canal Blockage.ipynb), 
[Bab el-Mandeb Strait](notebooks/Bab el-Mandeb Strait.ipynb), 
and [Bosporus Strait](notebooks/Bosporus Strait.ipynb) during periods of disruption. 
For Suez Canal, [re-routed 
vessels](Suez Canal Reroutes.ipynb) during the March 2021 blockage are also identified. 

To validate the algorithm, [transit counts for Suez Canal are compared 
with official data from Suez Canal Authority](notebooks/Suez Canal Benchmarking.ipynb). 

The notebooks are run in the [UN Global Platform](https://www.officialstatistics.org/). 
Connect to the platform and use kernel `pyspark3.5 ais2.9`.