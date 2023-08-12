hi<small>(c) 2021 - 2023 RENware Software Systems</small>

**Company Data API**

* Last released version: #FIXME what was the last one?

***

[TOC]

# CHANGELOG

<small markdown>
* For version code structure meaning see SDEVEN methodology document (*sic !*) :)

* with (F) are marked items that are features in order to be copied in a RELNOTE file

* with (B) are marked items thar are bug fixed previous versions

* -#NOTE ____ PUBLISHING IS MADE ON `dataapi.renware.eu` from `PUBLISHING` branch , wheen committed

</small>


## 1.0

* tbd... at a time drop or keep with name changed (as v0.99) old `articles_register.json` or move to a DEPRECATED area
* tbd... at a time drop or keep with name changed (as v0.99) old `products_register.json` or move to a DEPRECATED area



### 1.0.2 release products JSON broken down to entity level (#NOTE wip...)

* tbd... make a general review of Products Register then release

* wip...

* 230812piu_c add new JSON to `index.md` page and keep ref to old one and moved DEPRECATED VERSIONS to a different page accessible from navigator
* 230812piu_b add `meta_inf` key with (name, description, version, last update) sub-keys to `product_register` & rename old key for payload to `data`
* 230812piu_a moved `products_register` transform its payload data to array (list)
* (B) 230811piu_e `index.md` fix url path representation in HTML







### 1.0.1-release articles JSON broken down to entity level (230811 18:00)

* 230811piu_d review all articles API, refactored main JSON data entries as key **`data`**
* 230811piu_c refer new data src created in `230811piu_a`
* 230911piu_b introduced meta info *entity `name` & `description`* for entities created in `230811piu_a`
* 230811piu_a break _`articles_register.json`_ JSON in elementary entities and saved them in directory `articles/` ==>
  * `article_categories.json`
  * `articles_register.json`




### 1.0.0-release REN Products, Articles, MB APM course UNIT_01

* 230729piu_b change `index.md` API routes catalog to show route details as drill down admonition
* 230729piu_a upload from _RENpo_ `portal_structure.json` and extracted ONLY **PRODUCTS REGISTER** as `products_register.json`
* 230728piu_f updated `index.md` with details rwfAPI route (type, method)
* 230728piu_e made a simple logo of DataAPI project / site and other simple faceliftts
* 230728piu_d made first index page is a catalog of catalogs of API route and what they provide
* 230728piu_c created `data_sources/mb-apm-data/` and uploaded from TLP `unit_01.json`
* 230728piu_b uploaded from TLP `articles_register.json`
* 230728piu_a created `doc_src/data_sources/` directory for data sources


