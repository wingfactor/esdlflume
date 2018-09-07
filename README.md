# flume

### Environmental Systems and Dynamics Laboratory
#### University of California, Berkeley
___

Flume Experiment Data Repository

This repository was initiated during Fall 2018 to streamline data analysis and promote reproducibility of the experiments conducted from 2017 onwards.
___

Explanation of directory hierarchy:


- `data`: all original data generated by experiments
	- `raw`: raw data formats inherent to instrumentation and intermediate formats (partially processed but not yet tidy)
	- `tidy`: tidied data formats suitable for analysis
`prior`: data collected before Fall 2018 when reproducible workflow was implemented (note: presently in the process of extracting and tidying data as of 9/6/18)
	- note: metadata is included in tidy and raw data files/folders.


- `results`: results of data analysis, including graphics, tables, and documents in human-readable formats
	- `prior`: results from analysis performed before Fall 2018 when reproducible workflow was implemented


- `src`: source code for data tidying, analysis, and other purposes
	- `prior`: code for analysis  performed before Fall 2018 when reproducible workflow was implemented (to be updated)


- `doc`: supporting documents
	- `synthesis`: supporting articles (.pdf), supplementary material (.pdf), and parameters in a Excel workbook format, with Excel-dependent properties such as formulas and cell properties
	- `SOP`: standard operating procedures, calculations involved in methodology, and manuals for equipment used
___

File naming convention (applied 9/6/18 onwards and retroactively to some extent):

`{Location, Experiment, Etc,...} -- data specifics -- mm-dd-yyyy.extension`

If date is a range, use month abbreviations (ex: Mar 9-Apr 3 1991)


### TODO

- Eliminate prior folders
	- Tidy all data
	- Update raw data to naming convention
	- Update source code to new names of raw data
- Look into automating workflow with a Makefile or by using .Rmd
