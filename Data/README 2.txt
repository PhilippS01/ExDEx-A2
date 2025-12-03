*** Data underlying the paper: "Mapping the Market Potential for Air–Rail Integration on Substitutable Routes across Europe" ***
Author: F. Bruno
Division of Transport Planning, Department of Civil and Architectural Engineering, KTH Royal Institute of Technology

Contact Information:
frabruno@kth.se

***General Introduction***
This dataset contains the data underlying the paper: "Mapping the Market Potential for Air–Rail Integration on Substitutable Routes across Europe". The data is published both to substantiate the results of the paper and for other researchers to use in their own work.
The paper proposes a simple and interpretable indicator to quantify the market potential for air-rail integration on substitutable routes, where air and rail are concurrently available, across European airports.
The data made available in this repository includes an overview of railway station availability at European airports, and some indicators based on passenger flows, air travel times and travel times of rail alternatives, aggregated due to the limitations agreed with the data provider.
The data has been collected by the author either manually or through web scraping from multiple sources, including individual airport websites, Google Maps, OAG (both Schedules and Traffic), Rome2Rio and Signal.eu.org. 

***Methodological information***
The data, sources and methodology are described in detail in the paper "Mapping the Market Potential for Air–Rail Integration on Substitutable Routes across Europe".

***Detailed description of the data in this data set***
- Airports_Rail_Access.xlsx: list of the 317 airports analysed by the study, including:
							- Number and share of yearly passengers (2023) segmented by passenger type (point-to-point, spoke and hub passengers)
							- Number of yearly total and generated (spoke+ptp) passengers (2023)
							- Name, address, coordinates and UIC code of airport station (if any)
							- Railway infrastructure availability segmented by type (through, detour, branch line and linked to line)
							- Train service availability segmented by type (high-speed, long-distance and regional/suburban services)
							- Urban railway systems availability segmented by type (City-Airport Express Train, Train connection to City Station and Metro/Tram/People Mover)
- Candidate_Rail_Routes.xlsx: list of the 8.612 candidate alternative railway routes, based on scheduled air routes (OAG Schedules) between 15-11-2023 and 14-11-2024, including:
							- Airport OD
							- Name and coordinates of origin and destination of candidate alternative railway routes
							- Railway route (including railway lines used), distance and theoretical travel time (retrieved from Signal.eu.org)
							- Service travel time and mode (retrieved from Rome2Rio)
- Alternative_Rail_Routes_Unidirectional.xlsx: list of the 7.425 unidirectional alternative rail routes, including:
							- Unidirectional alternative rail route: name, origin, destination, coordinates
							- Travel times: rail theoretical (retrieved from Signal.eu.org), rail service (retrieved from Rome2Rio), air (from OAG Schedules), valued air (including min and max of sensitivity analysis range)
							- Passenger flows (passengers with rail alternatives available in case air-rail integration would be offered)
							- Indicators: teoretical and service ARISP, travel time difference and travel time increase (including min and max for sensitivity analysis range)
- Alternative_Rail_Routes_Bidirectional.xlsx: list of the 3.814 bidirectional alternative rail routes, including:
							- Bidirectional alternative rail route: name, origin, destination, coordinates
							- Travel times: rail theoretical (retrieved from Signal.eu.org), rail service (retrieved from Rome2Rio), air (from OAG Schedules), valued air
							- Passenger flows (passengers with rail alternatives available in case air-rail integration would be offered)
							- Indicators: teoretical and service ARISP, travel time difference and travel time increase
- Airports_Indicators.xlsx: list of the 58 airports with railway alternatives available at the airport, including:
							- Airport Name, IATA Code and Coordinates
							- Aggregated Yearly Passenger Flows: Potential (passengers with rail alternatives available), Connecting and Total passengers
							- ARISP Indicator aggregated at the airport level for Service and Theoretical Routes and their Delta