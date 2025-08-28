Ireland TUS:

TIER1:
- tier1 times taken from p. 20 and 21 of 79 (converted from hh:mm to hrs)
- hrs_per_day = hrs_per_weekday * (5/7) + hrs_per_weekend_day * (2/7)
- we took data that follows the priority listing below (if activities taken simultaneously, this determines which one is the main activity):
	1. childcare and adult care 
	2. employment and education 
	3. housework and shopping 
	4. travel 
	5. personal care and eating 
	6. leisure, voluntary and religious
	7. sleeping
	8. unspecified

TIER2:
- tier2 times taken from p. 17 of 79
- includes simultaneous activities (resulting in >24h)
- to re-weight the tier2 activities so they fit into 24 h), did the following:
	hrs_per_day for a tier2 = tier2 x (tier1/tier2_sum)
