# LaneJobs
Simple list of open positions in Lane County

Two approaches are implemented: 

PHP: eugenetech contains an index.htm file an associated eugenetech.php file, and jobs.csv. PHP code ingests jobs.csv, a coma-delimited text file with three columns: company names, links to jobs page, number of jobs. The PHP code generates HTML code that is inserted into index.htm. 

JavaScript: eugenetech_tt contains an index.htm file with embedded JavaScript. The javascript uses the TableTop framework to read data from a Google Docs table. 
