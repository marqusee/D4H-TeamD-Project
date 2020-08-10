The research problem:
Poor housing quality leads to poor health outcomes for renters in the City of Oakland, and the inequitable way in which this issue affects communities tends to be reflective of structural racism. Currently, the City of Oakland primarily responds to this issue via citizen complaints about housing habitability. It is likely that certain areas complain less about housing habitability due to a variety of factors, such as fear with respect to immigration status, language access, comfort with accessing city services, fear of landlord retribution, and other structural inequalities that prevent access. The City is working on a proactive enforcement system to provide equitable services but lacks a firm grounding in data.

The research question is:
What is the relationship between housing quality and structural racism in Oakland? More specifically:
What are the different characteristics of census tracts with low and high levels of housing habitability complaints? Are complaints most related to building characteristics or are race/ethnicity and other socioeconomic factors more significant?
Relevant data: race/ethnicity, income, rent burden, primary language spoken at home, poverty, overcrowding, building type, “legal units”
For context, the Alameda County Department of Public Health has asked for an analysis of the types of housing that have the most housing habitability complaints (i.e. number of units in building, age of building, and location of building) to improve program design and advocacy for a new inspection program.
Our hypothesis is that neighborhoods where there are large Latinx populations have disproportionately lower levels of housing habitability complaints compared to places with similar building types. People who are most likely to be impacted by housing habitability issues are often less likely to complain.

The data is:
ACS 5 year sample for SES data by census tract (2013-2018)
City of Oakland housing habitability complaints
https://aca.accela.com/OAKLAND/Welcome.aspx
In Google Drive folder
Assessor’s Database (tentative)
The method will be:
Data preparation
Bring in relevant ACS 5 year data (2018) into python for census tracts in the City of Oakland (Emma)
Bring in a geography for mapping City of Oakland by census tract
Bring in Oakland Code Enforcement. (Alex)
Create function to automatically download the data from the accela database
Create a ‘DATA PIPELINE’ that brings in accela database, performs search on the description field to identify whether the complaint is a housing habitability complaint (see earlier ACPHD report that has list of key words)
Descriptive Analysis of where complaints come from 
building typology, building age, tract,  neighborhood
How many complaints per census tract? Is this explained by building typology and age?
Does each census tract have the number of complaints you would expect? Determine analytically whether one can sufficiently explain the variance in housing habitability complaints with only building-specific data.
If structural racism & inequality is not playing a role, we would expect a proportionate amount of complaints across tracts given relevant housing stock (e.g. older buildings, high-unit density, etc.)
If not, what are the demographic/socioeconomic factors from the ACS that help explain lower or higher than expected levels of complaints?
The end product will be:
Dot map: complaints in Oakland (using addresses/parcels)
Choropleth: Aggregated complaints at tract level (continuous distribution)
Maps: typology of tracts in Oakland based on complaints (low, medium, high)
ALTERNATIVE: hotpot map (Patty to share info with the group about this).
Bar Charts: # Complaints per building characteristic (size of parcel, number of units, age)
Maps: Where are the relevant  building types located in Oakland?
Bar Charts: averages of census variables for each typology (or: for hotspots vs coldspots)
Maps: For each group of tracts matching the complaint typology/hotspot, display relevant census data
BONUS - turn it into a dashboard/webpage

