# RENware Data API

This site is used as company data provider.




## Project info

* p/n: `0000-0051`
* project code-name: `company_dataapi`
* start date: 2023 July 29
* author: Petre Iordanescu, `petre.iordanescu@gmail.com`




## Data formats

It basically returns `JSON` data (REST API style) but can also returns any other types of data formats *as files* (ie, like downloading a file).




## Routes and data processing

There are following type of *data returning URL routes*:

* **static routes** - these does not make any processing and just return file requested in route path as is

* **dynamic routes** - these make some server-side processing before sending data (usual as JSON but not mandatory in all cases)



