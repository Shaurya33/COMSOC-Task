An NOAA dataset has been stored in the file weather.csv.
This is the dataset I used for this task. The data for this task comes from The National Centers for Environmental Information (NCEI) Daily Global Historical Climatology Network (GHCN-Daily).

Each row in the task datafile corresponds to a single observation.

The following variables are provided to us:-

id : station identification code, 

date : date in YYYY-MM-DD format (e.g. 2012-01-24 = January 24, 2012), 

element : indicator of element type, 

TMAX : Maximum temperature (tenths of degrees C), 

TMIN : Minimum temperature (tenths of degrees C), 

value : data value for element (tenths of degrees C)

GOALS:-

1. Read the documentation and familiarize yourself with the dataset, then write some python code which returns a line graph of the record high and record low temperatures by day of the year over the period 2005-2014. The area between the record high and record low temperatures for each day should be shaded.

2. Overlay a scatter of the 2015 data for any points (highs and lows) for which the ten year record (2005-2014) record high or record low was broken in 2015.

3. Watch out for leap days (i.e. February 29th), it is reasonable to remove these points from the dataset for the purpose of this visualization.

4. Make the visual nice! Put in legends, labels and other beautifying stuff.
