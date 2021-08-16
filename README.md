# rideshare_proj_DSA
## Analysis of Boston Rideshare Platforms (Uber & Lyft)
**The Dataset**  
_Link to dataset on Kaggle: https://www.kaggle.com/brllrb/uber-and-lyft-dataset-boston-ma_  
- 57 Variables (40 of them relating to weather conditions - not used in analysis)  
- Variables used in analysis:  
	- Hour of the day (_hour of the ride_)  
	- Day of the Week (_day of the week_)  
	- Month in a year (_month of ride_)  
	- Date value (_complete date column_)  
	- Initial source of the ride (_pick-up location of ride_)  
	- Destination of the ride (_drop-off location of ride_)  
	- The type of cab (_Uber or  Lyft_)  
	- name (_type of ride offering from Uber and Lyft_)  
	- price (_price of ride for user_)  
	- distance (_total distance of each ride_)  
	- latitude (_latitude of pick-up location_)  
	- longitude (_longitude of pick-up location_)  
- Dataset originally contained ~70,000 rides documented between Nov. 26 - Dec. 18, 2018. Analyzed ~64,000 rides after cleaning NA values.  

**Research Questions Addressed in Analysis**  
- Overarching Question: _Given the (1) date, (2) time, (3) current location, (4) desired location, and (5) ride type, which rideshare service will be the most economically friendly in Boston?_  
- Sub-questions:
	- For Uber vs. Lyft...    
		- _Which neighborhoods are the most/least expensive to get a ride from?_  
		- _Which neighborhoods are the most/least expensive to get a ride to?_  
		- _Does either rideshare platform have varying pricing strategies with relation to time (day of the week, general time of the day, specific hours of the day)?_  
		- _Is there a difference in pricing when comparing the comparable ride types from either rideshare platform?_  

