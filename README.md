Made by:
 - Chris Rosendorf
 - Vikto Kim Christiansen
 - William Pfaffe

# Introduction
The needed dumps are in the file named `Dump20190405.sql`, all the needed csv files are also attached to this project

# 1
## Assignment 1
SELECT COUNT(*) FROM **parkregister**, **udsatte_by** WHERE ST_CONTAINS(**udsatte_by.wkb_geometry**, **parkregister.wkb_geometry**);

## Assignment 2
SELECT COUNT(*) FROM **gadetraer**, **udsatte_by** WHERE ST_CONTAINS(**udsatte_by.wkb_geometry**, **gadetraer.wkb_geometry**);

# 2

## Assignment 1

Due to data differences in cykelstativ and tungtrafik, we weren't able to compare data and get a valid materialized table out. We tried messing with SRID, although nothing really helped as much.