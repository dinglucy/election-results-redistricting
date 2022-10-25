# election-results-redistricting

The file in this repo is a work in progress. This is the product of an attempt to re-map election results in the 2012-2020 districts to the new 2022 districts on a precinct-by-precinct basis. Data comes primarily from [Dave's Redistricting](https://davesredistricting.org/maps#home). Errors are likely my own.

redist_results.csv includes:
* year - the year the election occured (2016, 2018, 2020).
* dem_2p - the Democatic two-party vote-share for a race at the top of the ballot in the district post-redistricting. Unless otherwise noted below, 2016 and 2020 uses data from the presidential election, and 2018 uses data from the governor's election, and if that doesn't exist, the senate election.
* district - the 2022 US House district.
* state - the state that the district is located in.

Notes:
* KY - 2019 Governor's race imputed for 2018 and 2020
* LA - 2019 Governor's race imputed for 2018
* MS - No data for Mississippi
* NC - Missing 2018 data
* NJ - Missing 2020 data
* NM - Missing 2020 data
* SD - Missing 2020 data
* WV - No data for West Virginia
