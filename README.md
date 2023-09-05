# ORI_PSAP_LOCODE
This project explores and connects information on law enforcement agencies, 911 centers (PSAPs) and other geographic aggregates such as LOCODE.

## Overview

While there is a substancial amount of research on both law enforcement departments and 911 communications departments, there is a lack of exploration around the intersection between the two. This may be the result of the fact that many 911 and communication centers are housed within law enforcement departments and thus appear synonmous. The location of these two departments are not always the same, and there appears to be a push across the country to house and run these departments seperate from one another. As a result it is important to understand the connection between communications/911 departments and the law enforcement agencies they dispatch to. Furthermore, getting a sence of the agreed upon geographic areas that LE and PSAPS cover nationally can give researchers, community members and departments a greater sense of how departments allocate their resources and the area in which different departments cover.

## Data Sources

- [IPCRS's Originating Agency Identifier (ORI) Crosswalk 2012](https://www.icpsr.umich.edu/web/ICPSR/series/366)
- [Homeland Infrastructure Foundation-Level's (HIFLD) 911 PSAP Service Area Boundaries](https://hifld-geoplatform.opendata.arcgis.com/datasets/psap-911-service-area-boundaries/explore)
- [United Nations UN/LOCODE](https://unece.org/trade/uncefact/unlocode)



## Project Caveats

- Physical datasets will not be hosted on this repository other than the final linked file
- This project utilizes both R and Python Coding
- Continuous Validation should be conducted on this project and the cooresponding sets as ORI information was last updated by ICPSR in 2012 and the PSAP map  most recent update is 2008-2009
