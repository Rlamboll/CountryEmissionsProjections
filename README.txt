# Regional emissions projections

This codebase takes a set of global emissions projections and imputes the R10 regional emissions that would most likely correspond to them. 

To run: 
1. Download AR6 data from https://data.ene.iiasa.ac.at/ar6/#/workspaces. We require at least the Emissions and price|CO2 variables, at R10 and global regional levels. Also download the metadata, AR6_Scenarios_Database_metadata_indicators_v1.1.
2. Put AR6 data in a folder marked "Input". Change the filename in notebook 01 to refer to the right files.
3. Run the notebooks in number order (this generates the emissions files)
4. Run the scripts 04 and 05. You may wish to modify 04 to run only some of the files in each pass. 
5. Results are all in the output folder.

This codebase runs along similar lines to 
"Credibility gap in net-zero climate targets leaves world at high risk"
https://www.science.org/doi/10.1126/science.adg6248