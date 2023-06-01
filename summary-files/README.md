# Summary Files

Values from the PVI model data and results files have been collected and are available here for easier accessibility. Model data and results files were regenerated weekly to incorporate data stream updates and to synchronize differences in release schedules. The files located here were created using data and results files that were regenerated on 12/21/2022. All files are linked to county level FIPS codes.

## File Organization

Static data are combined into a single file.

Dynamic data and model outputs are in timeseries files for each field.

All files are contained in pvi-summary-files.tgz for easier download.

## Date Ranges

Timeseries files will span different date ranges depending on the model.

Model 11.2.1: Feb 28, 2020 to March 28, 2022

Model 12.4: Jan 13, 2021 to March 28, 2022.

An end date of March 28, 2022, was chosen because several of the data streams began to deteriorate at that point. The individual model data and results files extend beyond this date, but the summary timeseries files do not.

## Data Inputs

### Static

Both models: AirPollution, DaytimePopDensity, Diabetes, Obesity, PctBlack, PctGE65, PctNative, PctNoIns, PrematureDeath, Smoking, SVIHousing, SVISocioeconomic, Traffic

11.2.1: PctBeds\*

### Dynamic

Both models: DistancingGrade, Sick, Spread

11.2.1: StatePctTested

12.4: PctBeds\*, PctVentilators, Testing, Vaccines

Extra\*\*: Cases, Deaths

## Model Outputs

Both models: PVIRank, PVIScore

------------------------------------------------------------------------

\* PctBeds exists in Model 11.2.1 as a static value and in Model 12.4 as dynamic

\*\* Cases and Deaths were not directly used in the models but are provided for convenience
