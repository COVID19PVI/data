# COVID-19 Pandemic Vulnerability Index (PVI) Dashboard

This is the public repository for the [COVID-19 Pandemic Vulnerability Index (PVI) Dashboard](https://covid19pvi.niehs.nih.gov/).  
</p><img src="https://github.com/COVID19PVI/data/blob/master/PVI-logo.jpeg" data-canonical-  
src="https://github.com/COVID19PVI/data/blob/master/PVI-logo.jpeg" />  
</p> 

## Quick Start Guide

The [Quick Start](https://www.niehs.nih.gov/research/programs/coronavirus/covid19pvi/) guide provides an overview of using the Dashboard.

## Documentation of Data Sources and Rationale

The current PVI model documentation, including data sources and performance evaluation, is available on the Dashboard [Details](https://www.niehs.nih.gov/research/programs/coronavirus/covid19pvi/details/) page.

## Models

The series of all daily PVI model files are posted in folders according to `<model-identifier>`. PVI model formulation (e.g. reapportionment of weights or incorporation of new source data) will change as new research advances our understanding of factors associated with vulnerability. [Model11.2.1](https://github.com/COVID19PVI/data/tree/master/Model11.2.1) is the PVI model displayed in the Dashboard upon loading that is selectable via the **PVI Model** button. It is built from data extending back to March 2020 and updated daily from data streams described at [Details](https://www.niehs.nih.gov/research/programs/coronavirus/covid19pvi/details/). 

There is now a new model, [Model12.4](https://github.com/COVID19PVI/data/tree/master/Model12.4), that is selectable in the Dashboard via the **PVI with Vaccine Model** button. This new model is built from data available since January 2021 and updated daily from data streams described at [Details](https://www.niehs.nih.gov/research/programs/coronavirus/covid19pvi/details/).

> **Results** files can be uploaded into the Dashboard. **Results** files are named as:</br>
>  `<model-identifier>_results_<date>.csv`.
>  
> **Data** files contain "raw" data prior to transformation into PVI using the [ToxPi  GUI](https://toxpi.org/). **Data** files can be manipulated using the [ToxPi  GUI](https://toxpi.org/) to generate new **Results** files for upload into the Dashboard. **Data** files are named as:</br>
>  `<model identifier>_data_<date>.csv`.

## Methods

Details of statistical methods are maintained in [Supplemental Methods](https://github.com/COVID19PVI/data/blob/master/COVID19PVI%20Supplemental%20Github.pdf). Descriptions of data columns for [Model11.2.1](https://github.com/COVID19PVI/data/tree/master/Model11.2.1) and [Model12.4](https://github.com/COVID19PVI/data/tree/master/Model12.4) are provided in [PVI Codebook](https://github.com/COVID19PVI/data/blob/master/PVI_codebook.pdf).

## Outreach & Education

A set of [COVID-19 PVI Lesson Plans](https://www.niehs.nih.gov/health/scied/teachers/covid-19/index.cfm), "Examining Risk Factors Associated With COVID-19 Using the Pandemic Vulnerability Index", has been developed by NIEHS for High School educators and students.

## Additional Resources

The COVID-19 Pandemic Vulnerability Index (PVI) Dashboard is mirrored as a [Your Community](https://covid.cdc.gov/covid-data-tracker/#pandemic-vulnerability-index) resource as part of the [CDC COVID Data Tracker](https://covid.cdc.gov/covid-data-tracker)

## Citation

https://doi.org/10.1289/EHP8690 [*Environmental Health Perspectives*]

https://doi.org/10.1101/2020.08.10.20169649 [*medRxiv* pre-print]

## Terms of Use

These data are provided under the GNU General Public License v3.0. Please see specific details for all data sources linked in our [Details](https://www.niehs.nih.gov/research/programs/coronavirus/covid19pvi/details/).

