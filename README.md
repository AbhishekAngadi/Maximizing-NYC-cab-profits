# Maximizing NYC Cab Profits

This project is the analysis of NYC cabs travel routes and fares earned. It further provides Recommendations to maximize profits earned and optimizing routes.

![Picture1](https://user-images.githubusercontent.com/44275206/82963986-3dda9c00-9f92-11ea-8060-ef6aa7664a44.jpg)

### Data Used: https://s3.amazonaws.com/nyc-tlc/trip+data/green_tripdata_2015-09.csv

### Recommendation Based on Analysis on Airport Trips

As per THE PORT AUTHORITY OF NY & NJ's monthly summary (DEC 2015), There are about 4.7 Million Passengers that travelled. As per the report about 890,000 passengers used Airport Coach(Bus), Taxis and Air Trains. The taxis dispatched were 202,000 approx.

Now, Assuming the numbers for September 2015 are 80% that of Dec 2015 (Since Dec is a high travel season usually). The numbers would now be: 3.76 total passengers. 708,000 passengers used Airport Coach(Bus), Taxis and Air Trains. The taxis dispatched were 161,000.

One needs to account for Ubers,Lyfts and other ride hailing companies too which is not stated in the report. As per https://www.businessinsider.com/uber-taxis-new-york-ridership-2017-10, these companies account for about 84% market share in 2015. Using the same market share numbers, if 161,000 taxis dispatched accounted for 16% market share, 84% accounts to 1.01 Million rides.

Of the total taxis dispatched and ride hailing cabs dispatched are about 1.17 million. Assuming only 20% of these travel from/to the green taxis zone, that's still 234K rides. While green taxis account for only 4276 rides (1.8%)!

The assumption is green taxis are not so popular, because ride hailing cabs (uber and lyft) are more convinient and cheaper.
So the Recommendation is to slash fare rates for airport trips to tap into this large market segment!!

Source: https://www.panynj.gov/airports/pdf/JFK_Dec_2015.pdf

### Recommendation based on analysis cab trips and hour of day:

The longest rides are taken early in the morning. Evenings have comparatively longer rides too. Hours between 9 and 7 have short rides taken. People take cabs to work to ensure they reach on time. Also, they take cab back home when it's really late. People do not take cab back home from work, if they leave on time. Since probably there is no urgency of reaching on time, they take the subway or other form of public transport

Hence, the recommendation is to Increase number of taxis at locations across NYC as per hour of the day. Also, cash tips need be tracked as well.

### Interesting Observation and Hypothesis:

People definitely prefer short distances over long distances. That's probably because of two reasons: Longer distances are extremely expensive. NY subway or driving their own car would be much cheaper. Secondly, longer distances could also mean increased traffic and longer trip times. NY subway would be a faster means of transport.

### FUTURE SCOPE 1:
Analyze data with other months and more importantly later year. Is there a drop is usage because of Uber/Lfyt?
### FUTURE SCOPE 2:
Anomaly Detection

