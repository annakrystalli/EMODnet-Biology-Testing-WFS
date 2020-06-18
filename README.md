# Test `EMODnetWFS` and `OBIShmpr` packages

## Introduction

Often researchers are interested in acceding data on species occurences and matching them to local environmental parameters.

Package `OBIShmpr` allows researchers to perform such queries to OBIS and then to match the resulting occurrences to a large number of publically available marine environmental data layers.

One of this data sources is EMODnet WFS. Acces to these data is now possible through a lightweight wrapper package `EMODnetWFS`.

## Directory structure

```
{{directory_name}}/
├── analysis
├── data/
│   ├── derived_data/
│   └── raw_data/
├── docs/
├── product/
└── scripts/
```

* **analysis** - Markdown or Jupyter notebooks
* **data** - Raw and derived data
* **docs** - Rendered reports
* **product** - Output product files
* **scripts** - Reusable code

## Data series

The first part of the work focused on the development of `EMODnetWFS`, a package for querying and downloading data from EMODnet WFS services.

[See vignette](https://annakrystalli.me/EMODnet-Biology-Testing-WFS/analysis/EMODnetWFS/)

The second part of the work explored using `OBIShmpr` to generate a dataset of species occurnences, matched to environmental by querying available online data services

[See vignette](https://annakrystalli.me/EMODnet-Biology-Testing-WFS/analysis/OBIShmpr/)


```
{{data_wfs_request}}
```

## Data product

{{data_product_description}}

## More information:

### References

### Code and methodology



### Citation and download link

This product should be cited as:

{{product_citation}}

Available to download in:

{{link_download}}

### Authors

{{product_authors}}
