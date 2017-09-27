---
title:  "ShakeCast Inventory Workbook (MS Excel)"
published: true
permalink: 2017_shakecast_inventory_workbook.html
summary: "Progress report on our extensively revised ShakeCast Workbook."
tags: ["software_update"]
---

The ShakeCast Inventory Workbook is a collection of Excel® spreadsheets used to bridge the gap between users' data and the ShakeCast application. It allows users to collect their facility, notification group, and user information in a single spreadsheet. Once the data have been collected, a customized function generates a master XML file that contains all the information needed for the user's ShakeCast instance.

A revision to the Workbook has been developed in the form of a spreadsheet specifically designed for the inclusion of building-specific HAZUS AEBM structural parameters. This spreadsheet is completely separable from the rest of the workbook, allowing users with the required information to take advantage of the AEBM without distracting users with less-detailed inventories.

The Workbook also serves as a stepping stone among Versions 2–4 of ShakeCast. It has the ability to import CSV and configuration files, which were used to upload data to V2. CSV files containing facility data can be exported from V2 and imported to the inventory workbook. This workbook will remain compatible with future versions of ShakeCast to ensure that installations of new software will be hassle-free.

There will be two forms of the Workbook: One, the _ShakeCast Workbook_, will serve primarily as the vehicle for getting inventory (building characteristics, including AEBM input values) into XML formats suitable for ShakeCast input. The ShakeCast Workbook will be part of the ShakeCast software distribution.

The other workbook, the _AEBM Workbook_, is in development. It is intended for expert (structural engineer) users to explore the HAZUS AEBM methodology ([Fig. 1](#fig1)) to see the effect of different choices on structural parameters on performance. One can also derive vulnerability functions and examine losses not typically provided with ShakeCast, including non-structural damage, dollar losses, and loss of function.

The ShakeCast Workbook will operate on ShakeMap input for the hazard values, whereas the stand-alone AEBM Workbook will require ground motion input (optionally from built-in GMPEs or from a ShakeMap intensity measures).


Fig. 1 – Snapshot of one of the many sheets of the ShakeCast AEBM Workbook. Users' structure inventory and notification databases can be developed in this Excel spreadsheet and exported as XML files for direct import into their ShakeCast software instance. This particular view shows the results of the performance point calculation, which serves to determine structure performance for the HAZUS AEBM methodology.

Contacts: David Wald (wald@usgs.gov); Kuo-wan Lin (Klin@usgs.gov); Daniel Slosky (dslosky@usgs.gov)