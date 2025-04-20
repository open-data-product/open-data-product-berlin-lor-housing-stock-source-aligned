
# Data Product Canvas - Berlin LOR Housing Stock (source-aligned)

## Metadata

* owner: Open Data Product
* description: Source-aligned data product providing Berlin LOR housing stock data
* url: https://github.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned
* license: CC-BY 4.0
* updated: 2025-06-07

## Input Ports

### Fortschreibung des Wohngebäude- und Wohnungsbestandes in Berlin 2015

* owner: Amt für Statistik Berlin-Brandenburg
* url: https://www.statistik-berlin-brandenburg.de/f-i-1-j
* license: CC-BY-3.0-Namensnennung
* updated: 2016-07-20

**Files**

* [SB_F01-01-00_2015j01_BE.xlsx](https://download.statistik-berlin-brandenburg.de/bd6c147896d2ff60/8bfec78484fb/SB_F01-01-00_2015j01_BE.xlsx)

### Fortschreibung des Wohngebäude- und Wohnungsbestandes in Berlin 2016

* owner: Amt für Statistik Berlin-Brandenburg
* url: https://www.statistik-berlin-brandenburg.de/f-i-1-j
* license: CC-BY-3.0-Namensnennung
* updated: 2017-06-23

**Files**

* [SB_F01-01-00_2016j01_BE.xlsx](https://download.statistik-berlin-brandenburg.de/ab9a0827a25a2614/7fe2b662af68/SB_F01-01-00_2016j01_BE.xlsx)

### Fortschreibung des Wohngebäude- und Wohnungsbestandes in Berlin 2017

* owner: Amt für Statistik Berlin-Brandenburg
* url: https://www.statistik-berlin-brandenburg.de/f-i-1-j
* license: CC-BY-3.0-Namensnennung
* updated: 2018-06-21

**Files**

* [SB_F01-01-00_2017j01_BE.xlsx](https://download.statistik-berlin-brandenburg.de/b3ee1cd3b49f141b/bb4d7164a0f2/SB_F01-01-00_2017j01_BE.xlsx)

### Fortschreibung des Wohngebäude- und Wohnungsbestandes in Berlin 2018

* owner: Amt für Statistik Berlin-Brandenburg
* url: https://www.statistik-berlin-brandenburg.de/f-i-1-j
* license: CC-BY-3.0-Namensnennung
* updated: 2019-06-28

**Files**

* [SB_F01-01-00_2018j01_BE.xlsx](https://download.statistik-berlin-brandenburg.de/a557654b00a58fb3/32cd91bd73de/SB_F01-01-00_2018j01_BE.xlsx)

### Fortschreibung des Wohngebäude- und Wohnungsbestandes in Berlin 2019

* owner: Amt für Statistik Berlin-Brandenburg
* url: https://www.statistik-berlin-brandenburg.de/f-i-1-j
* license: CC-BY-3.0-Namensnennung
* updated: 2020-06-24

**Files**

* [SB_F01-01-00_2019j01_BE.xlsx](https://download.statistik-berlin-brandenburg.de/fa35212b7514f205/fc5c0f8f8f61/SB_F01-01-00_2019j01_BE.xlsx)

### Fortschreibung des Wohngebäude- und Wohnungsbestandes in Berlin 2020

* owner: Amt für Statistik Berlin-Brandenburg
* url: https://www.statistik-berlin-brandenburg.de/f-i-1-j
* license: CC-BY-3.0-Namensnennung
* updated: 2021-07-06

**Files**

* [SB_F01-01-00_2020j01_BE.xlsx](https://download.statistik-berlin-brandenburg.de/6fe3f8c8d2c5c55a/d044eff304e4/SB_F01-01-00_2020j01_BE.xlsx)

### Fortschreibung des Wohngebäude- und Wohnungsbestandes in Berlin 2021

* owner: Amt für Statistik Berlin-Brandenburg
* url: https://www.statistik-berlin-brandenburg.de/f-i-1-j
* license: CC-BY-3.0-Namensnennung
* updated: 2022-07-12

**Files**

* [SB_F01-01-00_2021j01_BE.xlsx](https://download.statistik-berlin-brandenburg.de/490e783d37fff6c7/66730a658f1f/SB_F01-01-00_2021j01_BE.xlsx)

### Fortschreibung des Wohngebäude- und Wohnungsbestandes in Berlin 2022

* owner: Amt für Statistik Berlin-Brandenburg
* url: https://www.statistik-berlin-brandenburg.de/f-i-1-j
* license: CC-BY-3.0-Namensnennung
* updated: 2023-07-18

**Files**

* [SB_F01-01-00_2022j01_BE.xlsx](https://download.statistik-berlin-brandenburg.de/fc2a6d8be1b10993/3ed7d165d79a/SB_F01-01-00_2022j01_BE.xlsx)

### Fortschreibung des Wohngebäude- und Wohnungsbestandes in Berlin 2023

* owner: Amt für Statistik Berlin-Brandenburg
* url: https://www.statistik-berlin-brandenburg.de/f-i-1-j
* license: CC-BY-3.0-Namensnennung
* updated: 2024-06-19

**Files**

* [SB_F01-01-00_2023j01_BE.xlsx](https://download.statistik-berlin-brandenburg.de/08570921ab238985/ab0a7e58bc60/SB_F01-01-00_2023j01_BE.xlsx)

## Transformation Steps

* [Data extractor](../lib/extract/data_extractor.py) extracts data from inout ports
* [Data copier](../lib/transform/data_copier.py) copies and renames extracted data
* [Data CSV converter](../lib/transform/convert_data_to_csv.py) converts Excel files to CSV format
* [Data aggregator](../lib/transform/aggregate_data.py) aggregates data to be used as output ports

## Output Ports

### Berlin Lor Housing Stock 2015 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/tree/main/data/02-silver/berlin-lor-housing-stock-2015-00
* license: CC-BY 4.0
* updated: 2025-06-07

**Files**

* [berlin-lor-housing-stock-2015-00-1.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-1.csv)
* [berlin-lor-housing-stock-2015-00-10.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-10.csv)
* [berlin-lor-housing-stock-2015-00-11.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-11.csv)
* [berlin-lor-housing-stock-2015-00-12.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-12.csv)
* [berlin-lor-housing-stock-2015-00-13.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-13.csv)
* [berlin-lor-housing-stock-2015-00-14.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-14.csv)
* [berlin-lor-housing-stock-2015-00-15.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-15.csv)
* [berlin-lor-housing-stock-2015-00-16.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-16.csv)
* [berlin-lor-housing-stock-2015-00-17.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-17.csv)
* [berlin-lor-housing-stock-2015-00-18.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-18.csv)
* [berlin-lor-housing-stock-2015-00-2.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-2.csv)
* [berlin-lor-housing-stock-2015-00-3.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-3.csv)
* [berlin-lor-housing-stock-2015-00-4.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-4.csv)
* [berlin-lor-housing-stock-2015-00-5.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-5.csv)
* [berlin-lor-housing-stock-2015-00-6.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-6.csv)
* [berlin-lor-housing-stock-2015-00-7.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-7.csv)
* [berlin-lor-housing-stock-2015-00-8.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-8.csv)
* [berlin-lor-housing-stock-2015-00-9.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-9.csv)

### Berlin Lor Housing Stock 2016 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/tree/main/data/02-silver/berlin-lor-housing-stock-2016-00
* license: CC-BY 4.0
* updated: 2025-06-07

**Files**

* [berlin-lor-housing-stock-2016-00-1.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-1.csv)
* [berlin-lor-housing-stock-2016-00-10.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-10.csv)
* [berlin-lor-housing-stock-2016-00-11.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-11.csv)
* [berlin-lor-housing-stock-2016-00-12.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-12.csv)
* [berlin-lor-housing-stock-2016-00-13.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-13.csv)
* [berlin-lor-housing-stock-2016-00-14.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-14.csv)
* [berlin-lor-housing-stock-2016-00-15.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-15.csv)
* [berlin-lor-housing-stock-2016-00-16.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-16.csv)
* [berlin-lor-housing-stock-2016-00-17.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-17.csv)
* [berlin-lor-housing-stock-2016-00-18.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-18.csv)
* [berlin-lor-housing-stock-2016-00-2.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-2.csv)
* [berlin-lor-housing-stock-2016-00-3.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-3.csv)
* [berlin-lor-housing-stock-2016-00-4.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-4.csv)
* [berlin-lor-housing-stock-2016-00-5.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-5.csv)
* [berlin-lor-housing-stock-2016-00-6.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-6.csv)
* [berlin-lor-housing-stock-2016-00-7.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-7.csv)
* [berlin-lor-housing-stock-2016-00-8.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-8.csv)
* [berlin-lor-housing-stock-2016-00-9.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-9.csv)

### Berlin Lor Housing Stock 2017 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/tree/main/data/02-silver/berlin-lor-housing-stock-2017-00
* license: CC-BY 4.0
* updated: 2025-06-07

**Files**

* [berlin-lor-housing-stock-2017-00-1.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-1.csv)
* [berlin-lor-housing-stock-2017-00-10.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-10.csv)
* [berlin-lor-housing-stock-2017-00-11.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-11.csv)
* [berlin-lor-housing-stock-2017-00-12.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-12.csv)
* [berlin-lor-housing-stock-2017-00-13.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-13.csv)
* [berlin-lor-housing-stock-2017-00-14.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-14.csv)
* [berlin-lor-housing-stock-2017-00-15.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-15.csv)
* [berlin-lor-housing-stock-2017-00-16.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-16.csv)
* [berlin-lor-housing-stock-2017-00-17.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-17.csv)
* [berlin-lor-housing-stock-2017-00-18.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-18.csv)
* [berlin-lor-housing-stock-2017-00-2.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-2.csv)
* [berlin-lor-housing-stock-2017-00-3.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-3.csv)
* [berlin-lor-housing-stock-2017-00-4.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-4.csv)
* [berlin-lor-housing-stock-2017-00-5.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-5.csv)
* [berlin-lor-housing-stock-2017-00-6.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-6.csv)
* [berlin-lor-housing-stock-2017-00-7.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-7.csv)
* [berlin-lor-housing-stock-2017-00-8.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-8.csv)
* [berlin-lor-housing-stock-2017-00-9.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-9.csv)

### Berlin Lor Housing Stock 2018 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/tree/main/data/02-silver/berlin-lor-housing-stock-2018-00
* license: CC-BY 4.0
* updated: 2025-06-07

**Files**

* [berlin-lor-housing-stock-2018-00-1.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-1.csv)
* [berlin-lor-housing-stock-2018-00-10.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-10.csv)
* [berlin-lor-housing-stock-2018-00-11.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-11.csv)
* [berlin-lor-housing-stock-2018-00-12.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-12.csv)
* [berlin-lor-housing-stock-2018-00-13.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-13.csv)
* [berlin-lor-housing-stock-2018-00-14.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-14.csv)
* [berlin-lor-housing-stock-2018-00-15.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-15.csv)
* [berlin-lor-housing-stock-2018-00-16.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-16.csv)
* [berlin-lor-housing-stock-2018-00-17.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-17.csv)
* [berlin-lor-housing-stock-2018-00-18.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-18.csv)
* [berlin-lor-housing-stock-2018-00-2.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-2.csv)
* [berlin-lor-housing-stock-2018-00-3.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-3.csv)
* [berlin-lor-housing-stock-2018-00-4.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-4.csv)
* [berlin-lor-housing-stock-2018-00-5.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-5.csv)
* [berlin-lor-housing-stock-2018-00-6.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-6.csv)
* [berlin-lor-housing-stock-2018-00-7.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-7.csv)
* [berlin-lor-housing-stock-2018-00-8.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-8.csv)
* [berlin-lor-housing-stock-2018-00-9.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-9.csv)

### Berlin Lor Housing Stock 2019 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/tree/main/data/02-silver/berlin-lor-housing-stock-2019-00
* license: CC-BY 4.0
* updated: 2025-06-07

**Files**

* [berlin-lor-housing-stock-2019-00-1.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-1.csv)
* [berlin-lor-housing-stock-2019-00-10.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-10.csv)
* [berlin-lor-housing-stock-2019-00-11.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-11.csv)
* [berlin-lor-housing-stock-2019-00-12.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-12.csv)
* [berlin-lor-housing-stock-2019-00-13.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-13.csv)
* [berlin-lor-housing-stock-2019-00-14.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-14.csv)
* [berlin-lor-housing-stock-2019-00-15.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-15.csv)
* [berlin-lor-housing-stock-2019-00-16.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-16.csv)
* [berlin-lor-housing-stock-2019-00-17.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-17.csv)
* [berlin-lor-housing-stock-2019-00-18.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-18.csv)
* [berlin-lor-housing-stock-2019-00-2.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-2.csv)
* [berlin-lor-housing-stock-2019-00-3.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-3.csv)
* [berlin-lor-housing-stock-2019-00-4.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-4.csv)
* [berlin-lor-housing-stock-2019-00-5.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-5.csv)
* [berlin-lor-housing-stock-2019-00-6.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-6.csv)
* [berlin-lor-housing-stock-2019-00-7.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-7.csv)
* [berlin-lor-housing-stock-2019-00-8.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-8.csv)
* [berlin-lor-housing-stock-2019-00-9.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-9.csv)

### Berlin Lor Housing Stock 2020 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/tree/main/data/02-silver/berlin-lor-housing-stock-2020-00
* license: CC-BY 4.0
* updated: 2025-06-07

**Files**

* [berlin-lor-housing-stock-2020-00-1.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-1.csv)
* [berlin-lor-housing-stock-2020-00-10.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-10.csv)
* [berlin-lor-housing-stock-2020-00-11.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-11.csv)
* [berlin-lor-housing-stock-2020-00-12.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-12.csv)
* [berlin-lor-housing-stock-2020-00-13.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-13.csv)
* [berlin-lor-housing-stock-2020-00-14.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-14.csv)
* [berlin-lor-housing-stock-2020-00-15.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-15.csv)
* [berlin-lor-housing-stock-2020-00-16.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-16.csv)
* [berlin-lor-housing-stock-2020-00-17.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-17.csv)
* [berlin-lor-housing-stock-2020-00-18.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-18.csv)
* [berlin-lor-housing-stock-2020-00-2.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-2.csv)
* [berlin-lor-housing-stock-2020-00-3.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-3.csv)
* [berlin-lor-housing-stock-2020-00-4.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-4.csv)
* [berlin-lor-housing-stock-2020-00-5.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-5.csv)
* [berlin-lor-housing-stock-2020-00-6.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-6.csv)
* [berlin-lor-housing-stock-2020-00-7.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-7.csv)
* [berlin-lor-housing-stock-2020-00-8.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-8.csv)
* [berlin-lor-housing-stock-2020-00-9.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-9.csv)

### Berlin Lor Housing Stock 2021 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/tree/main/data/02-silver/berlin-lor-housing-stock-2021-00
* license: CC-BY 4.0
* updated: 2025-06-07

**Files**

* [berlin-lor-housing-stock-2021-00-1.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-1.csv)
* [berlin-lor-housing-stock-2021-00-10.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-10.csv)
* [berlin-lor-housing-stock-2021-00-11.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-11.csv)
* [berlin-lor-housing-stock-2021-00-12.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-12.csv)
* [berlin-lor-housing-stock-2021-00-13.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-13.csv)
* [berlin-lor-housing-stock-2021-00-14.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-14.csv)
* [berlin-lor-housing-stock-2021-00-15.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-15.csv)
* [berlin-lor-housing-stock-2021-00-16.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-16.csv)
* [berlin-lor-housing-stock-2021-00-17.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-17.csv)
* [berlin-lor-housing-stock-2021-00-18.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-18.csv)
* [berlin-lor-housing-stock-2021-00-2.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-2.csv)
* [berlin-lor-housing-stock-2021-00-3.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-3.csv)
* [berlin-lor-housing-stock-2021-00-4.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-4.csv)
* [berlin-lor-housing-stock-2021-00-5.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-5.csv)
* [berlin-lor-housing-stock-2021-00-6.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-6.csv)
* [berlin-lor-housing-stock-2021-00-7.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-7.csv)
* [berlin-lor-housing-stock-2021-00-8.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-8.csv)
* [berlin-lor-housing-stock-2021-00-9.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-9.csv)

### Berlin Lor Housing Stock 2022 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/tree/main/data/02-silver/berlin-lor-housing-stock-2022-00
* license: CC-BY 4.0
* updated: 2025-06-07

**Files**

* [berlin-lor-housing-stock-2022-00-1.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-1.csv)
* [berlin-lor-housing-stock-2022-00-10.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-10.csv)
* [berlin-lor-housing-stock-2022-00-11.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-11.csv)
* [berlin-lor-housing-stock-2022-00-12.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-12.csv)
* [berlin-lor-housing-stock-2022-00-13.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-13.csv)
* [berlin-lor-housing-stock-2022-00-14.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-14.csv)
* [berlin-lor-housing-stock-2022-00-15.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-15.csv)
* [berlin-lor-housing-stock-2022-00-16.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-16.csv)
* [berlin-lor-housing-stock-2022-00-17.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-17.csv)
* [berlin-lor-housing-stock-2022-00-18.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-18.csv)
* [berlin-lor-housing-stock-2022-00-2.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-2.csv)
* [berlin-lor-housing-stock-2022-00-3.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-3.csv)
* [berlin-lor-housing-stock-2022-00-4.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-4.csv)
* [berlin-lor-housing-stock-2022-00-5.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-5.csv)
* [berlin-lor-housing-stock-2022-00-6.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-6.csv)
* [berlin-lor-housing-stock-2022-00-7.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-7.csv)
* [berlin-lor-housing-stock-2022-00-8.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-8.csv)
* [berlin-lor-housing-stock-2022-00-9.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-9.csv)

### Berlin Lor Housing Stock 2023 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/tree/main/data/02-silver/berlin-lor-housing-stock-2023-00
* license: CC-BY 4.0
* updated: 2025-06-07

**Files**

* [berlin-lor-housing-stock-2023-00-1.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-1.csv)
* [berlin-lor-housing-stock-2023-00-10.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-10.csv)
* [berlin-lor-housing-stock-2023-00-11.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-11.csv)
* [berlin-lor-housing-stock-2023-00-12.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-12.csv)
* [berlin-lor-housing-stock-2023-00-13.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-13.csv)
* [berlin-lor-housing-stock-2023-00-14.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-14.csv)
* [berlin-lor-housing-stock-2023-00-15.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-15.csv)
* [berlin-lor-housing-stock-2023-00-16.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-16.csv)
* [berlin-lor-housing-stock-2023-00-17.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-17.csv)
* [berlin-lor-housing-stock-2023-00-18.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-18.csv)
* [berlin-lor-housing-stock-2023-00-2.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-2.csv)
* [berlin-lor-housing-stock-2023-00-3.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-3.csv)
* [berlin-lor-housing-stock-2023-00-4.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-4.csv)
* [berlin-lor-housing-stock-2023-00-5.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-5.csv)
* [berlin-lor-housing-stock-2023-00-6.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-6.csv)
* [berlin-lor-housing-stock-2023-00-7.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-7.csv)
* [berlin-lor-housing-stock-2023-00-8.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-8.csv)
* [berlin-lor-housing-stock-2023-00-9.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/02-silver/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-9.csv)

### Berlin Lor Housing Stock 2015 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/tree/main/data/03-gold/berlin-lor-housing-stock-2015-00
* license: CC-BY 4.0
* updated: 2025-06-07

**Files**

* [berlin-lor-housing-stock-2015-00-10-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-10-planning-areas.csv)
* [berlin-lor-housing-stock-2015-00-11-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-11-planning-areas.csv)
* [berlin-lor-housing-stock-2015-00-12-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-12-planning-areas.csv)
* [berlin-lor-housing-stock-2015-00-13-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-13-planning-areas.csv)
* [berlin-lor-housing-stock-2015-00-14-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-14-planning-areas.csv)
* [berlin-lor-housing-stock-2015-00-15-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-15-planning-areas.csv)
* [berlin-lor-housing-stock-2015-00-16-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-16-planning-areas.csv)
* [berlin-lor-housing-stock-2015-00-17-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-17-planning-areas.csv)
* [berlin-lor-housing-stock-2015-00-18-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-18-planning-areas.csv)
* [berlin-lor-housing-stock-2015-00-2-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-2-districts.csv)
* [berlin-lor-housing-stock-2015-00-4-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-4-districts.csv)
* [berlin-lor-housing-stock-2015-00-6-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-6-districts.csv)
* [berlin-lor-housing-stock-2015-00-7-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-7-planning-areas.csv)
* [berlin-lor-housing-stock-2015-00-8-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-8-planning-areas.csv)
* [berlin-lor-housing-stock-2015-00-9-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-9-planning-areas.csv)

### Berlin Lor Housing Stock 2016 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/tree/main/data/03-gold/berlin-lor-housing-stock-2016-00
* license: CC-BY 4.0
* updated: 2025-06-07

**Files**

* [berlin-lor-housing-stock-2016-00-10-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-10-planning-areas.csv)
* [berlin-lor-housing-stock-2016-00-11-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-11-planning-areas.csv)
* [berlin-lor-housing-stock-2016-00-12-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-12-planning-areas.csv)
* [berlin-lor-housing-stock-2016-00-13-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-13-planning-areas.csv)
* [berlin-lor-housing-stock-2016-00-14-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-14-planning-areas.csv)
* [berlin-lor-housing-stock-2016-00-15-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-15-planning-areas.csv)
* [berlin-lor-housing-stock-2016-00-16-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-16-planning-areas.csv)
* [berlin-lor-housing-stock-2016-00-17-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-17-planning-areas.csv)
* [berlin-lor-housing-stock-2016-00-18-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-18-planning-areas.csv)
* [berlin-lor-housing-stock-2016-00-2-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-2-districts.csv)
* [berlin-lor-housing-stock-2016-00-4-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-4-districts.csv)
* [berlin-lor-housing-stock-2016-00-6-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-6-districts.csv)
* [berlin-lor-housing-stock-2016-00-7-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-7-planning-areas.csv)
* [berlin-lor-housing-stock-2016-00-8-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-8-planning-areas.csv)
* [berlin-lor-housing-stock-2016-00-9-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-9-planning-areas.csv)

### Berlin Lor Housing Stock 2017 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/tree/main/data/03-gold/berlin-lor-housing-stock-2017-00
* license: CC-BY 4.0
* updated: 2025-06-07

**Files**

* [berlin-lor-housing-stock-2017-00-10-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-10-planning-areas.csv)
* [berlin-lor-housing-stock-2017-00-11-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-11-planning-areas.csv)
* [berlin-lor-housing-stock-2017-00-12-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-12-planning-areas.csv)
* [berlin-lor-housing-stock-2017-00-13-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-13-planning-areas.csv)
* [berlin-lor-housing-stock-2017-00-14-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-14-planning-areas.csv)
* [berlin-lor-housing-stock-2017-00-15-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-15-planning-areas.csv)
* [berlin-lor-housing-stock-2017-00-16-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-16-planning-areas.csv)
* [berlin-lor-housing-stock-2017-00-17-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-17-planning-areas.csv)
* [berlin-lor-housing-stock-2017-00-18-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-18-planning-areas.csv)
* [berlin-lor-housing-stock-2017-00-2-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-2-districts.csv)
* [berlin-lor-housing-stock-2017-00-4-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-4-districts.csv)
* [berlin-lor-housing-stock-2017-00-6-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-6-districts.csv)
* [berlin-lor-housing-stock-2017-00-7-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-7-planning-areas.csv)
* [berlin-lor-housing-stock-2017-00-8-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-8-planning-areas.csv)
* [berlin-lor-housing-stock-2017-00-9-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-9-planning-areas.csv)

### Berlin Lor Housing Stock 2018 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/tree/main/data/03-gold/berlin-lor-housing-stock-2018-00
* license: CC-BY 4.0
* updated: 2025-06-07

**Files**

* [berlin-lor-housing-stock-2018-00-10-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-10-planning-areas.csv)
* [berlin-lor-housing-stock-2018-00-11-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-11-planning-areas.csv)
* [berlin-lor-housing-stock-2018-00-12-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-12-planning-areas.csv)
* [berlin-lor-housing-stock-2018-00-13-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-13-planning-areas.csv)
* [berlin-lor-housing-stock-2018-00-14-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-14-planning-areas.csv)
* [berlin-lor-housing-stock-2018-00-15-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-15-planning-areas.csv)
* [berlin-lor-housing-stock-2018-00-16-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-16-planning-areas.csv)
* [berlin-lor-housing-stock-2018-00-17-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-17-planning-areas.csv)
* [berlin-lor-housing-stock-2018-00-18-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-18-planning-areas.csv)
* [berlin-lor-housing-stock-2018-00-2-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-2-districts.csv)
* [berlin-lor-housing-stock-2018-00-4-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-4-districts.csv)
* [berlin-lor-housing-stock-2018-00-6-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-6-districts.csv)
* [berlin-lor-housing-stock-2018-00-7-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-7-planning-areas.csv)
* [berlin-lor-housing-stock-2018-00-8-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-8-planning-areas.csv)
* [berlin-lor-housing-stock-2018-00-9-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-9-planning-areas.csv)

### Berlin Lor Housing Stock 2019 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/tree/main/data/03-gold/berlin-lor-housing-stock-2019-00
* license: CC-BY 4.0
* updated: 2025-06-07

**Files**

* [berlin-lor-housing-stock-2019-00-10-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-10-planning-areas.csv)
* [berlin-lor-housing-stock-2019-00-11-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-11-planning-areas.csv)
* [berlin-lor-housing-stock-2019-00-12-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-12-planning-areas.csv)
* [berlin-lor-housing-stock-2019-00-13-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-13-planning-areas.csv)
* [berlin-lor-housing-stock-2019-00-14-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-14-planning-areas.csv)
* [berlin-lor-housing-stock-2019-00-15-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-15-planning-areas.csv)
* [berlin-lor-housing-stock-2019-00-16-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-16-planning-areas.csv)
* [berlin-lor-housing-stock-2019-00-17-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-17-planning-areas.csv)
* [berlin-lor-housing-stock-2019-00-18-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-18-planning-areas.csv)
* [berlin-lor-housing-stock-2019-00-2-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-2-districts.csv)
* [berlin-lor-housing-stock-2019-00-4-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-4-districts.csv)
* [berlin-lor-housing-stock-2019-00-6-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-6-districts.csv)
* [berlin-lor-housing-stock-2019-00-7-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-7-planning-areas.csv)
* [berlin-lor-housing-stock-2019-00-8-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-8-planning-areas.csv)
* [berlin-lor-housing-stock-2019-00-9-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-9-planning-areas.csv)

### Berlin Lor Housing Stock 2020 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/tree/main/data/03-gold/berlin-lor-housing-stock-2020-00
* license: CC-BY 4.0
* updated: 2025-06-07

**Files**

* [berlin-lor-housing-stock-2020-00-10-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-10-planning-areas.csv)
* [berlin-lor-housing-stock-2020-00-11-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-11-planning-areas.csv)
* [berlin-lor-housing-stock-2020-00-12-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-12-planning-areas.csv)
* [berlin-lor-housing-stock-2020-00-13-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-13-planning-areas.csv)
* [berlin-lor-housing-stock-2020-00-14-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-14-planning-areas.csv)
* [berlin-lor-housing-stock-2020-00-15-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-15-planning-areas.csv)
* [berlin-lor-housing-stock-2020-00-16-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-16-planning-areas.csv)
* [berlin-lor-housing-stock-2020-00-17-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-17-planning-areas.csv)
* [berlin-lor-housing-stock-2020-00-18-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-18-planning-areas.csv)
* [berlin-lor-housing-stock-2020-00-2-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-2-districts.csv)
* [berlin-lor-housing-stock-2020-00-4-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-4-districts.csv)
* [berlin-lor-housing-stock-2020-00-6-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-6-districts.csv)
* [berlin-lor-housing-stock-2020-00-7-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-7-planning-areas.csv)
* [berlin-lor-housing-stock-2020-00-8-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-8-planning-areas.csv)
* [berlin-lor-housing-stock-2020-00-9-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-9-planning-areas.csv)

### Berlin Lor Housing Stock 2021 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/tree/main/data/03-gold/berlin-lor-housing-stock-2021-00
* license: CC-BY 4.0
* updated: 2025-06-07

**Files**

* [berlin-lor-housing-stock-2021-00-10-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-10-planning-areas.csv)
* [berlin-lor-housing-stock-2021-00-11-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-11-planning-areas.csv)
* [berlin-lor-housing-stock-2021-00-12-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-12-planning-areas.csv)
* [berlin-lor-housing-stock-2021-00-13-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-13-planning-areas.csv)
* [berlin-lor-housing-stock-2021-00-14-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-14-planning-areas.csv)
* [berlin-lor-housing-stock-2021-00-15-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-15-planning-areas.csv)
* [berlin-lor-housing-stock-2021-00-16-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-16-planning-areas.csv)
* [berlin-lor-housing-stock-2021-00-17-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-17-planning-areas.csv)
* [berlin-lor-housing-stock-2021-00-18-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-18-planning-areas.csv)
* [berlin-lor-housing-stock-2021-00-2-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-2-districts.csv)
* [berlin-lor-housing-stock-2021-00-4-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-4-districts.csv)
* [berlin-lor-housing-stock-2021-00-6-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-6-districts.csv)
* [berlin-lor-housing-stock-2021-00-7-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-7-planning-areas.csv)
* [berlin-lor-housing-stock-2021-00-8-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-8-planning-areas.csv)
* [berlin-lor-housing-stock-2021-00-9-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-9-planning-areas.csv)

### Berlin Lor Housing Stock 2022 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/tree/main/data/03-gold/berlin-lor-housing-stock-2022-00
* license: CC-BY 4.0
* updated: 2025-06-07

**Files**

* [berlin-lor-housing-stock-2022-00-10-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-10-planning-areas.csv)
* [berlin-lor-housing-stock-2022-00-11-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-11-planning-areas.csv)
* [berlin-lor-housing-stock-2022-00-12-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-12-planning-areas.csv)
* [berlin-lor-housing-stock-2022-00-13-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-13-planning-areas.csv)
* [berlin-lor-housing-stock-2022-00-14-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-14-planning-areas.csv)
* [berlin-lor-housing-stock-2022-00-15-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-15-planning-areas.csv)
* [berlin-lor-housing-stock-2022-00-16-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-16-planning-areas.csv)
* [berlin-lor-housing-stock-2022-00-17-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-17-planning-areas.csv)
* [berlin-lor-housing-stock-2022-00-18-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-18-planning-areas.csv)
* [berlin-lor-housing-stock-2022-00-2-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-2-districts.csv)
* [berlin-lor-housing-stock-2022-00-4-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-4-districts.csv)
* [berlin-lor-housing-stock-2022-00-6-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-6-districts.csv)
* [berlin-lor-housing-stock-2022-00-7-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-7-planning-areas.csv)
* [berlin-lor-housing-stock-2022-00-8-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-8-planning-areas.csv)
* [berlin-lor-housing-stock-2022-00-9-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-9-planning-areas.csv)

### Berlin Lor Housing Stock 2023 00

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/tree/main/data/03-gold/berlin-lor-housing-stock-2023-00
* license: CC-BY 4.0
* updated: 2025-06-07

**Files**

* [berlin-lor-housing-stock-2023-00-10-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-10-planning-areas.csv)
* [berlin-lor-housing-stock-2023-00-11-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-11-planning-areas.csv)
* [berlin-lor-housing-stock-2023-00-12-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-12-planning-areas.csv)
* [berlin-lor-housing-stock-2023-00-13-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-13-planning-areas.csv)
* [berlin-lor-housing-stock-2023-00-14-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-14-planning-areas.csv)
* [berlin-lor-housing-stock-2023-00-15-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-15-planning-areas.csv)
* [berlin-lor-housing-stock-2023-00-16-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-16-planning-areas.csv)
* [berlin-lor-housing-stock-2023-00-17-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-17-planning-areas.csv)
* [berlin-lor-housing-stock-2023-00-18-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-18-planning-areas.csv)
* [berlin-lor-housing-stock-2023-00-2-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-2-districts.csv)
* [berlin-lor-housing-stock-2023-00-4-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-4-districts.csv)
* [berlin-lor-housing-stock-2023-00-6-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-6-districts.csv)
* [berlin-lor-housing-stock-2023-00-7-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-7-planning-areas.csv)
* [berlin-lor-housing-stock-2023-00-8-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-8-planning-areas.csv)
* [berlin-lor-housing-stock-2023-00-9-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/main/data/03-gold/berlin-lor-housing-stock-2023-00/berlin-lor-housing-stock-2023-00-9-planning-areas.csv)

## Classification

**The nature of the exposed data (source-aligned, aggregate, consumer-aligned)**

source-aligned


---
This data product canvas uses the template of [datamesh-architecture.com](https://www.datamesh-architecture.com/data-product-canvas).