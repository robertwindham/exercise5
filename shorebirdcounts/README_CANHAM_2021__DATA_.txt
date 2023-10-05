This  CANHAM_2021__DATA_README.txt file was generated on 2022-06-10 by Mark C Drever


GENERAL INFORMATION

1. Title of Dataset: Data from: Sandpipers go with the flow: Correlations between estuarine conditions and shorebird abundance at an important stopover on the Pacific Flyway.

2. Author Information
	Corresponding Investigator 
		Name: Mark C. Drever
		Institution: Environment and Climate Change Canada, Delta, British Columbia, Canada
		Email: mark.drever@ec.gc.ca

	Co-investigator 1
		Name: Rachel Canham
		Institution: Environment and Climate Change Canada, Delta, British Columbia, Canada

	Co-investigator 2
		Name: Scott A. Flemming
		Institution: Environment and Climate Change Canada, Delta, British Columbia, Canada

	Co-investigator 3
		Name: David D. Hope
		Institution: Environment and Climate Change Canada, Ottawa, Ontario, Canada
	
	


3. Date of data collection: 1991-2019

4. Geographic location of data collection: Brunswick Point, Roberts Bank, Delta, British Columbia, Canada

5. Funding sources that supported the collection of the data: Environment and Climate Canada, Government of Canada

6. Recommended citation for this dataset: Canham, Flemming et al. (2021), Data from: Sandpipers go with the flow: Correlations between estuarine conditions and shorebird abundance at an important stopover on the Pacific Flyway, Dryad, Dataset


DATA & FILE OVERVIEW

1. Description of dataset

These surveys focus on two abundant shorebird species, Western Sandpiper (Calidris mauri) and Dunlin (Calidris alpina), and are conducted at a large mudflat on Roberts Bank, Delta, British Columbia, approximately 35 km south of Vancouver. These survey counts began in 1991 and are conducted annually during the northern migration period (April and May). Species-specific counts are derived from total flock counts multiplied by an estimate of percentage composition of the two species. Survey methodology described in detail in Drever et al. (2014). 

The Brunswick Point study site (49°03′ N, 123°09′ W) extends over the southern third of Roberts Bank, and encompasses a large mudflat (tidal range = 0 – 3.8 m) separated from agricultural fields by a dike. Vegetation in the near shore sections of the mudflat is composed mostly of saltmarsh and bushes. Sediments in the mudflat range from soft mud to sand, and portions of the lower intertidal zone are covered with eelgrass (Zostera marina and Z. japonica). A causeway supporting a major port facility separates the mudflat from the remainder of Roberts Bank, and the dike is used for recreational purposes.


2. File List: 
	File 1 Name: Roberts Bank counts and correlates (1991-2019).csv
	File 1 Description: Shorebird counts and daily environmental correlates from Brunswick Point study site, Roberts Bank, Delta, British Columbia, Canada.

	
METHODOLOGICAL INFORMATION

Total flock counts. The number of total flock counts conducted annually varied from seven to 15 counts from 1991 to 1998. Beginning in 1999, counts were conducted either daily or every other day during spring migration for an annual replicate of 17 to 32 daily counts. The migration period began on 15 April each year and continued until <1000 birds were observed or until 15 May, whichever came first. This timing was chosen to overlap with the major pulse of Western Sandpiper migration and also captured peak Dunlin numbers.

Daily timing of surveys depended on the tide cycle; the start of surveys ranged between 05:45 and 19:00 hr. Counts were conducted at a tide height of 3.5 m, based on tidal predictions at Point Atkinson, British Columbia. This tide height ensured birds were close to shore, with sufficient mudflat exposed to present good feeding opportunities for shorebirds. Occasionally maximum daily tide heights did not reach 3.5 m, and counts on these days were conducted during the actual maximum tide heights.

Counts began at the southern end of the Brunswick Point dike where it meets the Roberts Bank Superport causeway. All birds visible on the mudflat were counted from a vehicle along a series of stops on the dike, for a total length of ~2.5 km. Birds were counted through a spotting scope mounted on the vehicle window, primarily for distant flocks, and through binoculars to count birds near the vehicle. Flocks were counted by an initial assessment of flock density, and then by counting blocks incrementally in 50s, 100s, 500s, or 1000s, according to flock size, in each successive field of view across a scan of the entire flock. In 1992, the number of birds in large flocks was estimated by multiplying the number of square metres of mudflat covered by the flock by the average number of sandpipers in several 1-m2 plots estimated by eye (Butler 1994).

Species composition: Only total flock counts were conducted prior to 1997, as deriving species-specific counts was complicated by the intermixing of Western Sandpipers and Dunlin in the large flocks. Species-specific counts are calculated as a product of total flock counts and percentage composition of different species. From 1997 onwards, relative species composition (ratio of Western Sandpipers to Dunlins) was estimated during supplementary counts as birds settled on the mudflats before or after the main shorebird counts described above. Numbers of Western Sandpipers and Dunlins were individually tallied along visually estimated 1 m wide strips that ran perpendicular from the dike to the water’s edge, and included both open mudflat and shallow water. Tallies of all strip counts were summed and the species proportion for that day was calculated as the number of each species counted divided by the total number of birds.


DATA-SPECIFIC INFORMATION FOR: Roberts Bank counts and correlates (1991-2019).csv

1. Number of variables: 19

2. Number of cases/rows: 540

3. Variable List: 
Year:	Year when count took place
DateR:	Date when count took place, format:YYYY-MM-DD
DOY:	Day of year when count took place. Jan 1 = Day 1
Total.count:	Total count of birds during survey (includes both Western Sandpiper and Dunlin)
pred.ratio:	Proportion of flock that is Western Sandpiper, value predicted from species ratio model, see Drever et al. (2014)
wesa.ratio:	Proportion of flock that is Western Sandpiper, observed value for that day
WESA:		Estimated number of Western Sandpipers in the total flock counts. WESA = Total.count x pred.ratio
DUNL:		Estimated number of Dunlin in the total flock counts. DUNL = Total.count x (1-pred.ratio)
PEFA:		Number of Peregrine Falcon observed during survey
MERL:		Number of Merlin observed during survey
avg.temp.day:	Daily mean air temperature (°C), recorded at the Vancouver International Airport (49°11′41.000″N, 123°11′02.000″W) 
Total.Precip..mm.:	Daily total precipitation (mm), recorded at the Vancouver International Airport (49°11′41.000″N, 123°11′02.000″W) 
Discharge:	Discharge (flow) rate of Fraser River as observed at Hope Station maintained by Environment and Climate Change Canada. Historical Hydrometric Data Search. Available from: https://wateroffice.ec.gc.ca/search/historical_e.html
elev.range:	Tidal amplitude. Total difference between daily maximum and minimum tidal height measured at Point Atkinson (49.3333°N, 123.2500°W)
u:	Westerly wind vector: A positive “u” vector indicates the strength of wind moving from the west
v:	Southerly wind vector: A positive “v” vector indicates the strength of wind moving from the south.
Windspd:	Wind speed (km/h), recorded at the Vancouver International Airport (49°11′41.000″N, 123°11′02.000″W) 
WindDeg:	Wind direction (°), recorded at the Vancouver International Airport (49°11′41.000″N, 123°11′02.000″W) 
IR:	Solar radiation, Solar radiation (W/m2) was recorded at the University of British Columbia Totem Field climate station (49.2562°N, 123.2494°W). Data avialable at: https://ibis.geog.ubc.ca/~achristn/data.html#download


4. Missing data codes: 
	NA

5. Abbreviations used: 
	WESA = Western Sandpiper Calidris mauri
	DUNL = Dunlin Calidris alpina
	PEFA = Peregrine Falcon Falco peregrinus
	MERL = Merlin Falco Falco columbarius

6. Other relevant information: 
	Survey methodology and calculations described in detail in Drever et al. (2014).  Drever, M. C., Lemon, M. J., Butler, R. W., & Millikin, R. L. (2014). Monitoring populations of western sandpipers and Pacific dunlins during northward migration on the Fraser River Delta, British Columbia, 1991–2013. Journal of Field Ornithology, 85(1), 10-22.

	R code to analyse temporal trends and correlations with environmental correlates can be found at: https://onlinelibrary.wiley.com/action/downloadSupplement?doi=10.1002%2Fece3.7240&file=ece37240-sup-0001-Supinfo.r

	This work was funded by the Canadian Wildlife Service and the Science and Technology Branch of Environment and Climate Change Canada. The University of British Columbia provided photon flux density data. 


