MEX 2019

Data taken from enut_2019_tabulados_basicos_estimaciones_puntales

 ---- CALCULATIONS ----

2 methods, shown as separate tabs in 'all_calculations' xlsx (yield same result)

1) hours_per_day = actual_participation_rate * participant_hours

--> Their 'tasa de participación' is not the actual participation rate since it is divided by the #participants in that 'theme', not divided by the total population
	-> actual participation rate as a fraction = #participants ('población') / total pop 12+

2) hours_per_day = absolute hours / total population

- for total pop 12+, used #participants in 'sleep'
	-> ie. for total average, although cuadro 1.2 indicates the population 12+ is 101 145 196, I used 101 145 172 (#participants in sleep) since sleep should have 100% participation rate

*'all calculations' xlsx contains tabs 1) using absolute hours (including passive care), 2) using absolute hours (excluding passive care), 3) using participation rate (including passive care)*

*'main_data' xlsx times include passive care. This way, total_hours_per_day adds to 24h. However, female_hours_per_day exceeds 24h then, so I've included data excluding passive care in 'all calculations' in case it's needed

---- RELEVANT DATA TABLES -----

Theme 3: Productive activities
-> Cuadro 3.1
	-> Cuadro 3.1's 'unpaid care work' activities (care for household members with illness and disabilities, those 0-5, those 0-14, those 15-59, those 60+) have the same naming and times as Cuadro 4.1's 'care' activities. This double counting has been greyed out in the cleaned TUS

Theme 4: Care
-> Cuadro 4.1
	-> this includes 'passive care', which is defined as 'actividad simultanea o secundaria en que se está al pendiente o al cuidado de otra persona mientras se realiza otra actividad (principal)'
	-> Cuadro 4.1C: excludes 'passive care': the overall hours_per_day only add up to 22.9
-> since the general activities (ie. 'care for household members 0-5') already aligned with the MOOGAL categories, there was no need to include the more detailed activities (ie. 'feeding' or 'washing') in the cleaned TUS
	-> also see comment for Cuadro 3.1

	
Theme 5: Community and volunteer work
-> Cuadro 5.1 and 5.3
	-> Combining Cuadro 5.1 and 5.3 yield the same total time as Cuadro 3.1's 'Unpaid work in support of other households and voluntary work' - this double counting has been greyed out in the cleaned TUS (kept 5.1 and 5.3 because they contain more detailed activities than 3.1)
	-> Summing times for 5.1's 'housework' & 'purchases, payments, procedures, repairs of that home' matches 3.1's 'domestic work'
	-> Summing times for 5.1's 'Caring for children under 6 years of age' & 'Caring for people from 6 to 59 years old' & 'Caring for people aged 60 and over' matches 3.1's 'Age-specific care for people from other households'
	-> Summing times for 5.1's detailed volunteer and community work matches 3.1's aggregated category

Theme 6: Personal care and study activities
	-> Cuadro 6.1
	-> Cuadro 6.6

Theme 7: Socializing and entertainment
	-> Cuadro 7.1