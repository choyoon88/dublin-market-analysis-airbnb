# Market Analysis in Dublin - Airbnb
(** To see how the work was done, please go to <b>[Airbnb Market Analysis Dublin.ipynb](https://github.com/choyoon88/dublin-market-analysis-airbnb/blob/main/Airbnb%20Market%20Analysis%20Dublin.ipynb)</b> (<i>`cmd` + `mouse left click`</i> to open on a new tab)

## Assignment
A new city manager for Airbnb has started in Dublin and wants to better understand:
- what guests are searching for in Dublin,
- which inquiries hosts tend to accept.

Based on the findings the new city manager will try to boost the number and quality of hosts in Dublin to fit the demands from guests. The goal of this challenge is to analyze, understand, visualize, and communicate the demand / supply in the market. For example you may want to look at the breakdown of start date day of the week, or number of nights, or room type that is searched for, and how many hosts accepted the reservation. In particular, we are interested in:
- what the gaps are between guest demand and host supply that the new city manager could plug to increase the number of bookings in Dublin,
- what other data would be useful to have to deepen the analysis and understanding.

## Conclusion

We need to know the following info which are,
- what guests are searching for in Dublin,
- which inquiries hosts tend to accept.

### 1. What guests are searching in for in Dublin
- Most of the guests in Dublin were in small in size; `solo or couple` traveler and were looking for a room that could accomodate them only for a `short period` of time. It was mostly `less than a week` and `1-4 days` were most popular.

### 2. Which inquires hosts tend to accept
- Hosts like to accept the inquiry message during their free time of the day; `9-10pm` which is considered to be a chilling time for most of the people, time to wrap up their day and getting ready to sleep, hosts tend to reply the most during that hours.
- Peculiar case with `India` showing a high tendency of `hosts not accepting their inquiry`. While most of the countries showed a similar numbers of inquiry being accepted and not, India was outstanding with their rejection number.

We have two business requirements which are,
- BR1: what the gaps are between guest demand and host supply that the new city manager could plug to increase the number of bookings in Dublin,
- BR2: what other data would be useful to have to deepen the analysis and understanding.

### 1. BR1
- Dublin showed to be a very popular destination for visitors during `October`, but the pattern only showed during 2014. Need more investigation if the hosts were only actively advertising the accomodations on 2014 or if there was a promotion that lead the users to use the app actively during that time.

### 2. BR2
- There are top 5 countries that uses Airbnb the most; `'US', 'FR', 'GB', 'IE', 'IT'`. But the `booking rate of those countries were low or below average`.
- Investigated to see if the price being set too high and/or hosts repling too late to be the reason for the low booking rate for the top 5 countries, but it didn't show any significant pattern to understand the low booking rates.
- There should be more investigation needed with detailed data that contains the condition of the accomodations to acknowledge the reasoning of the low booking rates on top 5 countries.
