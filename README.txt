last update: 8 Jan 2025

****BEFORE RUNNING SCRIPTS****
- Download ImageJ v4.3.2 or later 
- Make sure Python is installed on your computer

###### steps to run ############
**if you do not need to crop images, upload images to .converted in .tif format
To crop images:
1. Copy images into ./imagej
2. Open ImageJ program
   > use ImageJ to run "getTerrotory_dark plate.txt" macro
**Pocessed images will appear in ./converted


To run script:
1. Open key.csv and edit the following:
                                  - date (e.g. 05012025, 06012025... etc)
                                  - group (e.g. CA10, CA11)
                                  - concentration (e.g. OP50, BVZD.. etc)
			***NOTE: Make sure these information are in the filenames
				 of each image (e.g. 05012025_CA10_OP50_B_1.tif)
                                  - change "parameter" column as necessary (can leave as it is for default)
4. Double click "Wormspot.bat"
5. View results:
	- Individual image predictions: converted > detect > check
	- Individual predicted counts: deadoralive_counts.csv
	- Summarised predicted counts: deadoralive_counts_summary.csv
	*summarised counts r based on key.csv groups 