Bay Area Bike Share Analysis
===


The City of Philadelphia and its partners at Bicycle Transit Systems are pleased to share anonymized Indego trip data:

1.) Indego_bike_prediction.ipynb (Modeling & feature analsis)

 Model = Regression, BDT

2.) Trip_summary_2018.ipynb(Data analysis)

Data: https://www.rideindego.com/about/data/

trip_id: Locally unique integer that identifies the trip

duration: Length of trip in minutes

start_time: The date/time when the trip began, presented in ISO 8601 format in local time

end_time: The date/time when the trip ended, presented in ISO 8601 format in local time

start_station: The station ID where the trip originated (for station name and more information on each station see the Station Table)

start_lat: The latitude of the station where the trip originated

start_lon: The longitude of the station where the trip originated

end_station: The station ID where the trip terminated (for station name and more information on each station see the Station Table)

end_lat: The latitude of the station where the trip terminated

end_lon: The longitude of the station where the trip terminated

bike_id:  Locally unique integer that identifies the bike

plan_duration: The number of days that the plan the passholder is using entitles them to ride; 0 is used for a single ride plan (Walk-up)

trip_route_category: “Round Trip” for trips starting and ending at the same station or “One Way” for all other trips
passholder_type: The name of the passholder’s plan

