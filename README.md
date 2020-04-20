# Open-Data

# County Pricing and Provider Data
This data utilizes BroadbandNow's proprietary plans and pricing data of over 4000 terrestrial broadband providers and the FCC's latest Form 477 data.

### Data Fields Appended to the broadband_data
Wired Providers 25 Mbps;
Terrestrial Providers 25 Mbps;
Wired Providers 100 Mbps;
Terrestrial Providers 100 Mbps;
Wired Lowest Priced Plan 25 Mbps;
Terrestrial Lowest Priced Plan 25 Mbps;
Wired Lowest Priced Plan 100 Mbps;
Terrestrial Lowest Priced Plan 100 Mbps

### Data Definitions
Wired Providers 25 Mbps: The number of providers covering at least 1% of a county's population whose maximum download speed available in the county is at least 25 mbps and maximum available upload speed is at least 3 mbps. These providers also must service the residential market and be a wired technology (DSL, Cable, and Fiber).

Terrestrial Providers 25 Mbps: The number of providers covering at least 1% of a county's population whose maximum download speed available in the county is at least 25 mbps and maximum available upload speed is at least 3 mbps. These providers also must service the residential market and be a terrestrial technology (DSL, Cable, Fiber, and Fixed Wireless).

Wired Providers 100 Mbps: The number of providers covering at least 1% of a county's population whose maximum download speed available in the county is at least 100 mbps and maximum available upload speed is at least 3 mbps. These providers also must service the residential market and be a wired technology (DSL, Cable, and Fiber).

Terrestrial Providers 100 Mbps: The number of providers covering at least 1% of a county's population whose maximum download speed available in the county is at least 100 mbps and maximum available upload speed is at least 3 mbps. These providers also must service the residential market and be a terrestrial technology (DSL, Cable, Fiber, and Fixed Wireless).

Wired Lowest Priced Plan 25 Mbps: Of all the wired (DSL, Cable, and Fiber) providers covering at least 1% of a county's population whose maximum download speed available in the county is at least 25 mbps and maximum available upload speed is at least 3 mbps, the lowest priced internet-only plan (offering speeds of at least 25 mbps download and 3 mbps upload) that is currently available as of April 2020.

Terrestrial Lowest Priced Plan 25 Mbps: Of all the terrestrial (DSL, Cable, Fiber, and Fixed Wireless) providers covering at least 1% of a county's population whose maximum download speed available in the county is at least 25 mbps and maximum available upload speed is at least 3 mbps, the lowest priced internet-only plan (offering speeds of at least 25 mbps download and 3 mbps upload) that is currently available as of April 2020.

Wired Lowest Priced Plan 100 Mbps: Of all the wired (DSL, Cable, and Fiber) providers covering at least 1% of a county's population whose maximum download speed available in the county is at least 100 mbps and maximum available upload speed is at least 3 mbps, the lowest priced internet-only plan (offering speeds of at least 100 mbps download and 3 mbps upload) that is currently available as of April 2020.

Terrestrial Lowest Priced Plan 100 Mbps: Of all the terrestrial (DSL, Cable, Fiber, and Fixed Wireless) providers covering at least 1% of a county's population whose maximum download speed available in the county is at least 100 mbps and maximum available upload speed is at least 3 mbps, the lowest priced internet-only plan (offering speeds of at least 100 mbps download and 3 mbps upload) that is currently available as of April 2020.

## Data Notes
Providers are only counted if they cover at least 1% of a county's population (based on 2010 Census). Providers that cover less than 1% of the population of a county are not considered.
Only residential providers and plans are considered.
The regular monthly price (not temporary promotional pricing) is considered as the price unless the only known or advertised price for a plan is the promotional rate. 
All providers must have at least 3 mbps upload as the maximum available coverage in a county to be included.
Plans must have at least 3 mbps upload speed to be included. Those that we cannot verify the upload speed for are excluded. 
All plans are internet-only. TV and/or Phone inclusive plans (Double, Triple Play, etc) are not considered.
There are cases where a county has providers indicating coverage but no qualifying plans. This is marked as "No Current Active Qualifying Plans Recorded". There are a variety of reasons for this including no currently available plans of the required download and / or upload speed; the provider's plans are not yet within our database; the provider's plans are not up to date in our database; too much information is unknown to confirm that a plan fits the requirements (plan type, speed, or prices are unknown).

## QA Process
Random counties were spot checked for accuracy by looking through the census block logs and raw plan pricing data to verify accuracy.

## Version
This data is as of April 2020. Any plan that has been active in April 2020 was considered at their current active price. 

## Authors
Julia Tanberk - Manager of Analytics & Data Science at BroadbandNow (BroadbandNow.com)

## Questions
Please contact us at help@broadbandnow.com if you have questions about the data.

## License
The provided data is licensed under the Open Use of Data Agreement v1.0 - https://github.com/microsoft/Open-Use-of-Data-Agreement/blob/master/O-UDA-1.0.md
