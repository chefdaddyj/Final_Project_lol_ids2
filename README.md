# Final_Project_lol_ids2
Studying the most current restaurant inspection data from the NYC Dept of Health

The data set I will be using is from the NYC OpenData Project and can be found here: https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/xx67-kt59

I'm still working out a full set of questions I would like to answer about this data set and will probably focus mostly on EDA techniques learned in class.

The data set has 384,198 rows of data (Includes all reviews from restaurants dating back to 2014 (but markedly less data from this time frame than 2015+. There is also some weird data with 1900)), but I expect this to shorten after I remove a number of incomplete entries.

Questions to Explore:
1. What was the most common violation? The least common?
2. What was the most number of point violations accumulated? Recently a favorite Chinese restaurant scored 116 points, which is an exuberantly high number, and they were immediately closed.
3. Are there certain types of restaurants (Chinese, Latin American, Indian, etc.) that face more violations?
4. Which borough was the "cleanest?" The "dirtiest?"
5. Is there correlation between wealth/demographics of a neighborhood and how the restaurants are rated?
6. What would a heat map look like? Are there "hot beds" or pockets of dirty/clean restaurants? Could one predict which restaurants are likely to have rodent problems based on such a heat map? For example, if a certain area of Brooklyn was known to have lots of roach/mice problems, with what degree of certainty could one predict that a new restaurant would receive violations for mice? This could be addressed by first creating a heat map and then looking at restaurants that opened in the past year and see if they received similar violations.
7. Like the police often have unofficial quotas at the end of the month (resulting in a higher number of summons issued in the later part of the month), is there something similar with the NYC DOH? Do violations increase towards the end of the month?
8. Do cheaper restaurants have more violations because they might not be able to pay the fines/ fix the more expensive issues? Is it possible to merge Yelp (which gives an approximate cost ranging from $ - $$$$ to answer this?) Or maybe it just means cheaper places are less concerned with health code violations? Any way to distinguish the two?

Questions I don't know how to answer:
1. Having worked in the industry for many years, I know from first hand experience in multiple restaurants that an inspection from the DOH is extremely subjective to the individual conducting the inspection. It would be interesting to see which inspectors were the strictest/most harsh, but I don't believe this is data that has been released. Might not be answerable with the given data set.
