# Project title: Crash! Collisions in LA

### Link to proposal: https://github.com/fonduh/UP221-collisions/tree/main/Group%20Assignments#readme
____
#### Roles: Give each team member a title, and define what role each team member will play, and how each person plans to contribute to the project. While this may be subject to change, it is a good idea to define this early in the project to clarify "who is doing what."

**Leila:** Will map out the traffic collisions for 2020 overall and provide information about accidents, such as: Victim Age, Victim Sex, Victim Descent. Mapped out each of these variables by location as well. Doing some team project managment/organization. 

**Sonia:** Will map out the traffic collisions for 2020 overall and provide information Traffic Collision MO codes. These MO Codes show the specific type of collision, like vehicle vs. parked vehicle, non injury, and hit and run. Maybe map the patterns of types of traffic collisions onto two different geographies within LA City, like Westwood and East Hollywood.

**Fonda:** Will map how district characteristics (commercial vs residential vs industrial, density, etc.) factor into variances in collision frequency. Will dive into road quality and its impact on traffic collisions, potential link to allocated funding for road repairs and climate-related causes of damage such as heat
Data source for road conditions: https://data.lacity.org/City-Infrastructure-Service-Requests/Road-Surface-Condition-Map/d9rz-k88a 

**Nick:** Will map traffic collisions city wide for a given month, then filter out by time of day.

**Eisha:** Will look into weather data related to case study of collison, and provide statistics on the number of cases with specific safety equipment utilized, as well as levels of sobriety/drug involvement, by Case:ID
____
#### Status update: Report on the general mood of the team, and provide details as to what is working, and what is not.
General mood: Seemingly ok, maybe a little wary of moving forward because of our change in dataset only a few days ago. 

Other comments from specific team members:
* Eisha: Found 2 datasets associated with our collision file. One is called Party Victims. Provided statistics on the Geojson difficult to upload, just trying to get the LA Lat/Long. Geojson download, little option, draw a line, draw a square around the area to filter the data.
* Fonda: Figuring out how to query more data for collisions, found some traffic conditions data but not for all census tracts 
____
#### **Data update:** Provide a short narrative on where you are with the data sources you will incorporate in your project. Provide links as necessary.
We are going to use a new data set for the midterm. Some of our work that we did in week 3 won’t necessarily apply anymore to our final report. Based on our session with Chris, we’ve identified that our analysis of West LA is too narrowly focused and also ambiguous in terms of definition (i.e. West LA doesn’t have a clearly defined census tract / FIPS data or agreed upon neighborhood boundaries). 
We are instead using all of LA City as our geography.
____
#### **Concerns:** There should be a lot to be concerned about at this phase of the project. List those concerns and classify them as "Major concerns" and/or "Minor concerns."
**Major:** 
1. Having issues figuring out how to remove NA, missing, or empty values in the observations in order to report accurately. 
2. Haven’t been able to figure out how to re-label observations in the charts. I.e. code “H” corresponds to Hispanic. ← how do we get the charts to show a legend saying H = Hispanic, or re-lable the x-axis?
3. One member still struggling to figure out how to map folium files, and merge datasets

**Minor:** 
1. Are we able to find data sources about specific infrastructure issues about each intersection? Can we find a dataset of stop sign data to overlay? 
2. Landing on specific meeting times. We're figuring out together how to both work asynchronously, and also have a couple of virtual group meetings to discuss the project in live time. 
