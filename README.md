# NYC 2020 Tract to 2020 Election District Ratios

Code to derive the NYC 2020 Census Tract to the 2020 BOE Election District ratios for aggregating census data at the election district level. The election districts in turn can be rolled up to identify the socio-economic characteristics of voters at the poll site level for targeted outreach, understanding voting behavior better, etc. 

The attached ratio calculates for a given census tract, how many election districts overlap with it and by how much. After the 2020 Census Redistricting, BOE came up with 4,408 election districts. As per the 2020 Census Redistricting, there are 2,325 tracts.

Currently, the Census Bureau releases Decennial data at the Voter Tabulation Districts (VTD). According to Census Bureau, Voting Districts (VTDs) refer to the generic name for geographic entities, such as precincts, wards, and election districts, established by state governments for the purpose of conducting elections. The relationship between the election districts and VTD is usually 1-to-1. However, there are cases where two or more election districts are associated with
one VTD. The [New York State Legislative Task Force on Demographic Research and Reapportionment](https://latfor.state.ny.us/data/?sec=2020) recently came up with the mapping of Election Districts (as of 2018) to the 2020 Census VTD. 

However, since then, the BOE has changed the election districts boundaries given the 2020 Census Redistricting, necessitating the use of the attached tract-to-election district ratios in this folder. Furthermore, the ACS 5-year data doesn't publish data at the VTD level, which requires us to use another methodology to be able to apportion the tract level data to the election district/pollsite level.

