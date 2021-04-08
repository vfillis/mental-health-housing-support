First: divided data frames into before April 2019 and since April 2019 because the data frames were restructured from April 2019. So I had to look at them separately to bring them into the same structure to then merge them 

-	MHSDS data frame is an extensive collection of mental health services data 
o	End of year data as it is revised / providers can resubmit data and it is therefore more accurate 
o	From April 2019: data in a new format, requires to analyse and merge the data from April 2019 to today and the data up to March 2019 separately 


April 2019
Were in one folder and then used command line to merge the 20 data frames. 

I merged the 20 CSVs using the command line (cat *.csv > MHSDS2019to2020.csv) after navigating with “cd” to the folder containing the CSVs. 

Then continued in R.  

Results-based
-	Analysed data over time, so e.g. from April 2019 to today, but whenever there was no change (in most cases) I referred to the latest data or the average over time (so it’s always around 8% that are in employment, etc.) 
o	No chart, only in text OR infographic with main facts (how many on CPA, % of all in contact with adult MH services, in accommodation, in employment, on CPA for 12 months, …) 
-	

