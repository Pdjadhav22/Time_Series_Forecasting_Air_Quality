# Time_Series_Forecasting_Air_Quality
**Data Set Information:**
 -  This data set includes hourly air pollutants data from 12 nationally-controlled air-quality monitoring sites. The air-quality data are from the Beijing Municipal Environmental Monitoring Center. The meteorological data in each air-quality site are matched with the nearest weather station from the China Meteorological Administration. The time period is from March 1st, 2013 to February 28th, 2017. Missing data are denoted as NA.

**Problem Statement -**
  To predict Concentration of "PM2.5" on Daily Basis
  
**- Pre-Processing & Model Building steps**
1. Import Libraries
2. Load Dataset
3. EDA 
    - Insight - 
      1.  PM2.5 inversly correlated to Temp.
      2.  In winter season, i.e. at Start & End of Year PM2.5 is high
4. Missing value Handling
5. Decompse to get insight about Trend, Seasonality & residuals
6. Model Buuilding
    1.  SARIMAX Model
    2.  SARIMAX Model with permutation & combination of Parameterd
    3.  Auto ARIMA with Seasonality considered
    4.  Prophet Model
   
