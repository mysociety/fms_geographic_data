# FixMyStreet Geographic Count Data

This creates a number of different files at different levels of aggregation. It uses Elvis Nyanzu‘s (University of Sheffield) levels of categorisation to create counts at different levels that can be compared across the country. 

It aggregates counts of reports across several different metrics.

Two kinds of interface aggregation:

* FixMyStreet - reports made through FixMyStreet.com
* Cobrand - reports made through FixMyStreetPro co-brands

Two kinds of geographic aggregation:

* LSOA - Lower Super Output Area (in Scotland and Northern Ireland switches to Datazones and SOA).
* LAD - Local Authority Districts. 

Four kinds of category aggregation:

* All Reports - count of all reports
* SHEF_A -  Reconciliation of different category names into 94 categories
* SHEF_B -  Reconciliation of different category names into 29 B categories.
* SHEF_C - Reconciliation of different category names into 9 C categories. 

Three kinds of time aggregation:

* Month
* Year
* All Time

For each it provides a the number of reports for each geographic unit, and the number of users who filed those reports (and gives an average number of reports per user in area/time/category.).

Counts are split between reports made on fixmystreet.com (inc apps) and those made through co-branded pro websites. 

To generate using the fms export tool use 'process.py export geo'.

Read more about the FMS Export process [here](https://docs.google.com/document/d/1caU_2Fh8tkhbw8Lw54ho5iCb248EnRz1v_O6ah_H7KU/edit#heading=h.2qy3r7t6u34b)

