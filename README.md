# Module4b-Programming-Assignment2
This is the second Peer Graded Assignment for Module 4b

The Enviromental Protection Agency(EPA) tracks the emissions of fine particulate matter (PM2.5) and releases the database on emissions every 3 years.  The database is known as the National Emissions Inventory (NEI). For each year and for each type of PM source, the NEI records how many tons of PM 2.5 were emitted from that source over the course of the entire year.

Data : Souce_Classification_Code.rds(This table provides a mapping from the SCC digit strings in the Emissions table to the actual name of
                                     the PM2.5 source. The sources are categorized in a few different ways from more general to more
                                     specific and you may choose to explore whatever categories you think are most useful. For example,
                                     source “10100101” is known as “Ext Comb /Electric Gen /Anthracite Coal /Pulverized Coal”.
       summarySCC_PM25.rds          (This file contains a data frame with all of the PM2.5 emissions data for 1999, 2002, 2005, and 2008.
                                     For each year, the table contains number of tons of PM2.5 emitted from a specific type of source for 
                                     the entire year)

Year : 1999, 2002, 2005 and 2008

Unit of measure : tons


fips: A five-digit number (represented as a string) indicating the U.S. county
SCC: The name of the source as indicated by a digit string (see source code classification table)
Pollutant: A string indicating the pollutant
Emissions: Amount of PM2.5 emitted, in tons
type: The type of source (point, non-point, on-road, or non-road)
year: The year of emissions recorded



