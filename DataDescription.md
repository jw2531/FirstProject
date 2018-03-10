Data Descripton
================

### Part 2: Description of Data

1. Source of the data:

  * https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Historic/qgea-i56i
  * API access via SODA API: https://data.cityofnewyork.us/resource/9s4h-37hy.csv
  
  * This dataset includes all valid felony, misdemeanor, and violation crimes reported to the New York City Police Department (NYPD) from 2006 to the end of last year (2016).
  
  * The dataset is provided by NYPD and owned by NYC OpenData. It has 5.58 Million rows and 24 variables. 3 types of variables included are number, text, and location. The 24 variables are listed below.
  
Column&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Description  
CMPLNT_NUM(number)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Randomly generated persistent ID for each complaint  
CMPLNT_FR_DT(Date&Time)&nbsp;"Exact date of occurrence for the reported event (or starting date of occurrence, if CMPLNT_TO_DT exists)"  
CMPLNT_FR_TM(text)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"Exact time of occurrence for the reported event (or starting time of occurrence, if CMPLNT_TO_TM exists)"  
CMPLNT_TO_DT(Date&Time)&nbsp;"Ending date of occurrence for the reported event, if exact time of occurrence is unknown"  
CMPLNT_TO_TM(text)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"Ending time of occurrence for the reported event, if exact time of occurrence is unknown"  
RPT_DT(Date&Time)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Date event was reported to police  
KY_CD(number)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Three digit offense classification code  
OFNS_DESC(text)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Description of offense corresponding with key code  
PD_CD(number)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Three digit internal classification code (more granular than Key Code)  
PD_DESC(text)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Description of internal classification corresponding with PD code (more granular than Offense Description)  
CRM_ATPT_CPTD_CD(text)&nbsp;&nbsp;"Indicator of whether crime was successfully completed or attempted, but failed or was interrupted prematurely"  
LAW_CAT_CD(text)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"Level of offense: felony, misdemeanor, violation"  
JURIS_DESC(text)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"Jurisdiction responsible for incident. Either internal, like Police, Transit, and Housing; or external, like Correction, Port Authority, etc."  
BORO_NM(text)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The name of the borough in which the incident occurred  
ADDR_PCT_CD(number)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The precinct in which the incident occurred  
LOC_OF_OCCUR_DESC(text)&nbsp;"Specific location of occurrence in or around the premises; inside, opposite of, front of, rear of"  
PREM_TYP_DESC(text)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"Specific description of premises; grocery store, residence, street, etc."  
PARKS_NM(text)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"Name of NYC park, playground or greenspace of occurrence, if applicable (state parks are not included)"  
HADEVELOPT(text)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"Name of NYCHA housing development of occurrence, if applicable"  
X_COORD_CD(number)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"X-coordinate for New York State Plane Coordinate System, Long Island Zone, NAD 83, units feet (FIPS 3104)"  
Y_COORD_CD(number)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"Y-coordinate for New York State Plane Coordinate System, Long Island Zone, NAD 83, units feet (FIPS 3104)"  
Latitude(number)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"Latitude coordinate for Global Coordinate System, WGS 1984, decimal degrees (EPSG 4326) "  
Longitude(number)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"Longitude coordinate for Global Coordinate System, WGS 1984, decimal degrees (EPSG 4326)"  
Lat_Lon(location)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Combined Latitude and Longitude coordinates  
