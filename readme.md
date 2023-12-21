## README

Repository for my final project related to a project I have completed and my goal is to transform it with thesisdown and macdown into a reproducible format!

The scope of this project entails analyzing an existing bus route in Hamilton and then seeing how it can be optimized. The bus route being analyzed in this project will be 52 Dundas.

# Chapter 1: Route Alignment 
___

## 1.1 Route Directness
Using Google Maps and Remix, the roundtrip distance, actual length of the route and the shortest path between the start-end stops were determined. In the northbound direction, the 52 Dundas route starts from Orchard at Pleasant and ends at Watson’s Lane Loop. In the southbound direction, the 52 Dundas route starts from Watson's Lane Loop and ends at Orchard at Pleasant. The roundtrip distance for the 52 Dundas route from northbound to southbound is 10.49 km. The actual length of the route is 5.2 km in both directions (northbound and southbound). The shortest path between the start-end stops is 5.1 km in both directions (northbound and southbound). Generally known, the ratio indicates the route directness. The ratio between the shortest path and the actual route is 0.98 in both directions meaning the route is quite direct.

## 1.2 Service Coverage

According to the census data, and route characteristics from OpenStreetMaps, the population size served by the route is approximately 8245 in both directions. The service coverage area within 400 m of the local bus. Below are some statistics that outline the following characteristics.

52 Dundas route characteristics:
Roundtrip Distance: 10.49 km

Actual Route Length: 5.2 km (inbound) ; 5.2 km (outbound)

Shortest Path: 5.1 km

Ratio: 0.98

Population: 8245

Holistic Land Use: Residential

Current Route Operation Cost: $144.9 k/year

##1.3 Land Use

The northbound and southbound transit routes for 52 Dundas are both mainly comprised of residential land use considering it provides service to an area that is predominantly surrounded by housing infrastructure. Both directions also have few commercial and institutional land uses. This information was extracted with Remix.

#2 Stop Accessibility
In this section, using Google Earth and Remix, the exact number of stops on Route 52, and what amenities at each stop were identified. Google Street View at each stop was used to see what infrastructure is in place at each stop. 

There are 19 stops in the southbound route which begins at Watson Lane Loop, and ends at Orchard at Pleasant. In the southbound route, 12 of the stops which make up 67% of stops, only had a post and sidewalk as infrastructure. 6 stops (33%) had benches, and only 2 (11%) of those stops had shelters.

There are 18 stops in the northbound route which starts at Orchard at Pleasant stop and ends at Watson Lane Loop stop. In the northbound route, 13 stops (76%) only had a post as infrastructure, of which only 6 had sidewalks. There are 4 stops with benches (24%) where only 1 of those stops has a shelter as well. The York at Cootes stop is served by a Sobi Hub, making it the only stop either north or southbound to have that privilege.

#3 Service Frequency and Fleet
The purpose of analyzing the service frequency of an existing transit system is to ensure that the level of service has adequate space to accommodate the maximum number of on-board passengers along the entire route over a given time period. Using Remix, both inbound and outbound timetable data were extracted to analyze both the weekday and weekend frequencies and fleet size.

##3.1 Frequency Weekday
The frequency weekday was analyzed for both inbound and outbound directions by graphing the
average frequency of the existing service for certain time intervals. Based on the frequency data patterns observed for both inbound and outbound, the level of frequency was consistent along the entire route over different time periods for all stops. This was the case for 52 Dundas considering there was not much change in the level of service along the route. To represent the frequency weekday for this route, the frequency of the inbound stop Orchard at Pleasant, and the outbound stop Watson’s Lane Loop were used as a benchmark. The maximum frequency for both inbound and outbound is 1.67 buses/hr which occurs during both 06:30 – 09:30 AM and 15:00 – 18:00 PM peak hours.

##3.2 Frequency Weekend
Currently, Route 52 Dundas is not scheduled to run during weekends, hence the frequency for the weekend is zero. It could be that there is not enough demand or ridership during the weekends for the 52 Dundas area. This could be something to reconsider when reconfiguring the route.

##3.3 Fleet Size
The fleet size for Route 52 is 2 buses for both time periods during the Weekday. As Route 52 does not run-on weekends, there are no fleet sizes reported. The maximum fleet is 2 buses. The buses run every 30 minutes so for the first time period, there is one bus per hour and for the second time period, there is one bus every hour and a half.

#4 Service Demand
Route 52 only runs during the periods of A.M. peak, midday and P.M. peak. Based on this we
decided to allocate 34% to the A.M. peak, 32% to the midday period and the last 34% to the P.M. peak. In the data folder, the distribution of boardings at each stop along the route associated with each time period are detailed. From these results, load profile graphs can be generated. This is where the images of the figures should be displayed, however, it was unable to knit.

#5 Service Evaluation
Using the data file labelled "Load Profile Analysis" to begine analyzing the how frequency changes throughout the time periods in a day. In order to evaluate the service utilization, the current frequency and the optimal frequency in each direction must be compared. Based on the steps, the results should be as follows.

For the AM/PM peaks, the current frequency is higher than optimal and therefore the allocated service is over-utilized. Ideally the frequency should be decreased to the minimum of 1 bus per hour to save costs and avoid running empty buses. For the mid-day time period the frequency was 0 as no buses were running at the time however by analyzing the data from task 4 and 5 we can see that the frequency can be brought up to the minimum of 1 bus per hour to accommodate the demand for mid-day service. 


# Conclusion

A simple analysis was completed for 52 Dundas route in an effort to observe the existing system’s infrastructure through changes in operational quality, service quality, and overall connectedness of the transportation grid. From these results, different reconfigurations could be made based on minimizing costs or improving the service within communities in close proximity to the 52 Dundas HSR route. However, it is important to note that there is no perfect, silver-bullet solution for this route or any route for that matter.

The data provided as well as the process of extracting these results have been outlined within this project. File naming, version control with Github, determining the appropriate tools (R Studio and Excel) to use, identifying the infrastructure and then creating a process flow were completed. This project can hopefully be reproduced and repeated with the data and the instructions provided. 

On a personal note, it has been a huge learning experience for me. I have been able to learn many new skills that I did not have at the start of this semester. I came into this course with null knowledge of R and Github and it is amazing what I can now do with the skills I have! Thank you so much Antonio!

