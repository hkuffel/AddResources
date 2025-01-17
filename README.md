# ShelterApp
``````
Shelter App Inc., is an all volunteer non-profit organization whose mission is to help homeless and low-income families connect to services using web and mobile app.
``````
## Getting Started: 

#### Shelter app currently supports following types and sub-types of the services hence all the scrapped data should fall under one or more of these.
Type | Service Sub Type
-- | --
FOOD	| Food Pantry, Soup Kitchen
SHELTER	| Transitional Shelter, Transitional Housing, Emergency Shelter
HEALTH	| Medical Clinic, Mental Health Services
RESOURCES	| Miscellaneous Services, Support Services, Legal Assistance, Senior Resources
WORK	| 

#### Scrapping guidelines and rules.
We have to have follow general scraping guilelines mentioned here for all our scrappers.
https://github.com/ShelterApp/AddResources/wiki#scraping-guidelines--standards


#### This repo is created to Add resources by web crawling on below open data platforms
(https://drive.google.com/drive/folders/1V652EVRsCLHznKfHXIHylIREYbmsc3MB?usp=sharing)

1. IRS Links for Data Extraction: 
   - https://www.irs.gov/charities-non-profits/exempt-organizations-business-master-file-extract-eo-bmf
   - https://www.irs.gov/pub/irs-soi/eo_info.pdf
    
    *NTEE Codes of Interest:
    154 Health clinic
    166 Mental health care
    380 Low-income housing
    381 Low and moderate income housing
    566 Job training, counseling, or assistance
    B70 Libraries
    D40 Veterinary Services
    D99 Animal-Related N.E.C.
    E21 Community Health Systems
    E30 Health Treatment Facilities, Primarily Outpatient
    E32 Ambulatory Health Center, Community Clinic
    E50 Rehabilitative Medical Services
    E60 Health Support Services
    F32 Community Mental Health Center
    F40 Hot Line, Crisis Intervention Services
    F42 Rape Victim Services
    F60 Counseling, Support Groups
    F99 Mental Health, Crisis Intervention N.E.C.
    I80 Legal Services
    I83 Public Interest Law, Litigation
    J22 Vocational Training
    J99 Employment, Job Related N.E.C.
    K30 Food Service, Free Food Distribution Programs
    K31 Food Banks, Food Pantries
    K34 Congregate Meals
    K36 Meals on Wheels
    K99 Food, Agriculture, and Nutrition N.E.C.
    L30 Housing Search Assistance
    L40 Low-Cost Temporary Housing
    L41 Homeless, Temporary Shelter For
    L80 Housing Support Services -- Other
    L99 Housing, Shelter N.E.C.
    O20 Youth Centers, Clubs, Multipurpose
    O31 Big Brothers, Big Sisters
    O50 Youth Development Programs, Other
    O99 Youth Development N.E.C.
    P24 Salvation Army
    P26 Volunteers of America
    P30 Children's, Youth Services
    P40 Family Services
    P42 Single Parent Agencies, Services
    P43 Family Violence Shelters, Services
    P46 Family Counseling
    P51 Financial Counseling, Money Management
    P52 Transportation, Free or Subsidized
    P60 Emergency Assistance (Food, Clothing, Cash)
    P72 Half-Way House (Short-Term Residential Care)
    P81 Senior Centers, Services
    P82 Developmentally Disabled Centers, Services
    P84 Ethnic, Immigrant Centers, Services
    P85 Homeless Persons Centers, Services
    P86 Blind/Visually Impaired Centers, Services
    P87 Deaf/Hearing Impaired Centers, Services
    P99 Human Services - Multipurpose and Other N.E.C.
    
2. CareerOneStop Link for Employment Assistance Resources:
   - https://www.careeronestop.org/Developers/Data/comprehensive-and-affiliate-american-job-centers.aspx
   
3. HUD Links:
   - https://www.hudexchange.info/resource/3031/pit-and-hic-data-since-2007/
   - https://hudgis-hud.opendata.arcgis.com/
   
4. OpenStreetMap Download Links:
   - https://planet.openstreetmap.org/
   - https://wiki.openstreetmap.org/wiki/Tag:amenity=social%20facility?uselang=en
   
5. Washington State Resources form Northwest Hospitality:
     - https://www.nwhospitality.org/welcome-homeless-neighbor
     - https://airtable.com/shrkjUwUgqBU8vI1j/tblsz2z5rrnl9fdvG

6. NYC Homeless Drop-In Centers, After School Programs: Runaway & Homeless Youth, :
     - https://data.cityofnewyork.us/Social-Services/Directory-Of-Homeless-Drop-In-Centers/bmxf-3rd4
     - https://data.cityofnewyork.us/Social-Services/DYCD-after-school-programs-Runaway-And-Homeless-Yo/ujsc-un6m
     
7. Washington DC Homeless Services & Shelters
     - https://opendata.dc.gov/datasets/47be87a68e7a4376a3bdbe15d85de398_6
     - https://opendata.dc.gov/datasets/87c5e68942304363a4578b30853f385d_25/data?geometry=-77.467%2C38.810%2C-76.540%2C38.997
     
8. Miami Open 211 (No need to Scrape. Need to call through API directly to the app)
     - http://miami.open.211.developer.adopta.agency/

9. Baltimore Homeless Shelters
     - https://data.baltimorecity.gov/Health/Homeless-Shelters/hyq3-8sxr
     
10. Public Libraries in US
     - https://www.imls.gov/research-evaluation/data-collection/public-libraries-survey

11. Missouri Food Banks:
     - https://catalog.data.gov/dataset/food-pantry-list
     
12. California Food Resources:
     - https://controllerdata.lacity.org/resource/v2mg-qsxf.json
     
13. Canada Homeless Shelters:
     - https://open.canada.ca/data/en/dataset/7e0189e3-8595-4e62-a4e9-4fed6f265e10
    
14. BC Food Bank DataSet:
     - https://catalogue.data.gov.bc.ca/dataset/food-banks
