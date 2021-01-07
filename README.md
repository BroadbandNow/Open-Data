# Open-Data

# Zipcode Competition & Pricing Data
This data utilizes BroadbandNow's proprietary plans and pricing data of over 4000 terrestrial broadband providers and the FCC's latest Form 477 data.

### Updated 
1/6/2021: updated file to provide some missing US zip codes and correct formatting error

### Data Fields Appended to the broadband_data
Zip;
Population;
County;
State;
WiredCount_2020;
FWcount_2020;
AllProviderCount_2020;
Wired25_3_2020;
Wired100_3_2020;
All25_3_2020;
All100_3_2020;
TestCount_2020;
AverageMbps_2020;
FastestAverageMbps_2020;
%Access to Terrestrial Broadband_2020;
Lowest Priced Terrestrial Broadband Plan_2020;
WiredCount_2015;
FWcount_2015;
AllProviderCount_2015;
Wired25_3_2015;
Wired100_3_2015;
All25_3_2015;
All100_3_2015;


### Data Definitions
Zip: Zip Code

Population: Total Population of Zip Code (2010)

County: County

State: State

WiredCount: Number of Wired (Cable, Copper, DSL, Fiber) Providers present in a zip code

FWcount: Number of Fixed Wireless Providers (WISPs) present in a zip code

AllProviderCount: Number of Providers of any technology present in a zip code

Wired25_3: Number of Wired (Cable, Copper, DSL, Fiber) Providers present in a zip code offering speeds of at least 25 Mbps Download / 3 Mbps Upload

Wired100_3: Number of Wired (Cable, Copper, DSL, Fiber) Providers present in a zip code offering speeds of at least 100 Mbps Download / 3 Mbps Upload

All25_3: Number of Providers (any technology) present in a zip code offering speeds of at least 25 Mbps Download / 3 Mbps Upload

All100_3: Number of Providers (any technology) present in a zip code offering speeds of at least 100 Mbps Download / 3 Mbps Upload

TestCount: Number of M-Lab Speed Tests Conducted in Zip, rolling 12 months

AverageMbps: Average Download Speed via M-Lab Speed Tests, rolling 12 months

FastestAverageMbps: Fastest Average (90th Percentile) Download Speed via M-Lab Speed Tests, rolling 12 months

%Access to Terrestrial Broadband: Percent of the Zip's Population that has Access to Terrestrial (Wired + Fixed Wireless) Broadband (25 Mbps Download / 3 Mbps Upload)

Lowest Priced Terrestrial Broadband Plan: The Lowest Regular Monthly Priced Terrestrial (Wired + Fixed Wireless) Residential Standalone-Internet Broadband (25 Mbps Download / 3 Mbps Upload) Plan available in the zip

## Data Notes.
Coverage Data with a suffix "_2020" is from the current June 2019 477, suffix "_2015" is from June 2015 477.
Only residential providers and plans are considered.
Pricing data comes from publicly available plan data from more than 2,000 internet service providers in the third quarter of 2020.
The regular monthly price (not temporary promotional pricing) is considered as the price unless the only known or advertised price for a plan is the promotional rate.
All plans are internet-only. TV and/or Phone inclusive plans (Double, Triple Play, etc) are not considered.
There are cases where a zip has providers indicating coverage but no qualifying plans. In these cases, the Lowest Priced Terrestrial Broadband Plan is NULL.
The coverage data comes from the latest FCC form 477 reporting, which is enhanced and supplemented by provider coverage update submissions directly to BroadbandNow.  
Speed test data comes Measurement Lab network diagnostic tool speed tests. "							
							
## QA Process
Random zips were spot checked for accuracy by looking through the census block logs and raw plan pricing data to verify accuracy.

## Version
This data is published December 9, 2020 and is current as of October 2020. Any plan that has been active since July 2020 was considered at their current active price. 

## Authors
Julia Tanberk - Manager of Analytics & Data Science at BroadbandNow (BroadbandNow.com)

## License
This project is for the use of Microsoft Open Data and the Open Data Institute's Open Data Challenge.

## Attribution
This open data is available to the public, but we ask any person or organization who uses it provide the following attribution: 
Any direct republication or derivative works leveraging the BroadbandNow’s open data will include attribution to BroadbandNow, in the references section and/or on-page links and footnotes, as appropriate with a link in either of the formats: 

“ <a href="https://broadbandnow.com">BroadbandNow</a> ” 
“ <a href="https://broadbandnow.com/research">BroadbandNow Research</a> ”

BroadbandNow must be appropriately attributed if open data is either directly, or in a derivative form, is distributed to third-party media outlets for promotional purposes. 

