hi<small>(c) 2021 - 2023 RENware Software Systems</small>

**Company Data API**

* Last released version: #FIXME what was the last one?

***

[TOC]

# CHANGELOG

<small markdown>
* For version code structure meaning see SDEVEN methodology document (*sic !*) :)

* with (F) are marked those changes that are features in order to be copied in a RELNOTE file

* -#NOTE ____ PUBLISHING IS MADE ON `dataapi.renware.eu` from `PUBLISHING` branch , wheen committed

</small>


## 1.0

* tbd... at a time drop or keep with name changed (as v0.99) old `articles_register.json` or move to a DEPRECATED area

### 1.0.2 release ...same as 1.0.1 but for xxx (#NOTE wip...)




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


