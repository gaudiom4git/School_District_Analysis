# School_District_Analysis
#
## Overview

Students were asked to repeat steps in generating dataframes that show reading and math scores for a specific school and then repeat steps to generate summaries by
school, school district and school type to determine if there was some dishonesty in academic reporting by Thomas High School.

This module required students to utilize their Pandas dataframe and Series skills to set math and reading scores for the ninth grade in Thomas High School to NaN's (not a numeric) 
to see how the remaining grade summaries at Thomas High School are relative to the other schools and impact to district and school type summaries.

Functions such as loc() and map() functions were used to update and format data so that dataframes were properly presenting money and grades in a readable format.  The numpy
library also provided a way to identify NaN's.  NaN's were used to remove Thomas High School ninth grade data from the dataframe(s) to see if the other grades for the high
school affected overall school, district and school type numbers.

## Results

* Affect on District Summary:  
	Percentage passing math, reading, and overall passing dropped slightly    
	Check out [Distict Summary Comparison](https://github.com/gaudiom4git/School_District_Analysis/blob/main/Resources/SchoolDistrictComparison.png)
   
* Affect on School Summary:  
	For Thomas high school, average math went down, average reading went up, passing math went up, passing reading went down, and overall passing dropped slightly.
   
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?  
	This also didn't seem to change.  Thomas High School still ranked in the Top 5 Performing Schools
	
* How does replacing the ninth-grade scores affect the following:
    Math and reading scores by grade:
    Scores by school spending:		Same bin, no change
    Scores by school size	 :		No change
    Scores by school type	 :		No Change

## Summary

Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

The biggest difference when scores were replaced with NaNs were visible in Thomas High School's numbers.   

(1) Math scores increased after NaN's replaced
(2) Reading scores increased after NaN's replaced
(3) Overall passing scores also increased after NaN's reploaced 

Check out [Thomas HS scores before NaN replaced](https://github.com/gaudiom4git/School_District_Analysis/blob/main/Resources/ThomasHSBeforeNanReplace.png)

Check out [Thomas HS scores after NaN replaced](https://github.com/gaudiom4git/School_District_Analysis/blob/main/Resources/ThomasHSAfterNanReplaced.png)