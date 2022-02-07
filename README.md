Sakay.PH released an unofficial COMELEC offices datasets last February 2022. We utilized various datasets such as COMELEC and OpenStreetMap (OSM) data to generate a centralized geospatial database of the COMELEC offices. The initial COMELEC dataset was used to collect the relevant information of the offices including their addresses and contact numbers. For provinces  However, provinces outside Metro Manila have limited information, thus we used OSM data to collect the information for the municipal halls and centers. Moreover, COMELEC data for Antique, Oriental Mindoro, and some municipalities in Palawan (Puerto Princesa), Quirino (Aglipay), and Zamboanga Sibgay (Roseller Lim) are not available as these weren't part of the initial dataset from COMELEC.

The dataset contains the following columns:

**province**: string, province
**municipality**: string, municipality
**id**: string, concatenated municipality and province
**primary**: string, name of place for display
**secondary**: string, raw address of the COMELEC office
**lat**: double, latitude of the location
**lng**: double, longitude of the location 
**precise**: boolean, indicator for the precision of the COMELEC office location
**contact**: string, public phone number

This dataset was processed last August 2021. This is available for public consumption, under the Open Data Commons Open Database License (ODbL), and with proper attribution to Sakay and OpenStreetMap.