# benzene-pollution
Data analysis supporting the reporting of The Texas Tribune story, "Toxic benzene lingered for weeks after shelter-in-place warnings ended following 2019 Houston-area chemical fire"

The core data for this analysis came from dozens of CSV files provided by the Environmental Protection Agency. These files reflected about two months worth of data collected by an EPA air-monitoring van that drove around the Deer Park neighborhood outside of Houston, where a petrochemical fire burned in 2019, putting public health at risk. The truck recorded thousands of air quality readings, which were filtered using SQLite Studio. The full database of readings is in the SQL file in this Dropbox link: https://www.dropbox.com/scl/fi/gg3kvbkwpjvmo9lkz3sen/ITC_benzene_v2?rlkey=vj4icbj1cxkaljef9lh7tv8zg&dl=0 

To give you an idea of the type of queries and results used to report this story and build its graphics (without having to download the large SQL file) the results of one query, looking at benzene levels between 180 and 999 parts per billion by volume, are in the CSV file in this repository.
