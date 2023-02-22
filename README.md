```diff
- text in #ff6961
```

'''
```html
   // <h2 style="color:#ff6961"> Works in Progress TEST </h2> <ol  style="color:#A7C7E7">
```
'''

<h2 style="color:#ff6961"> Works in Progress TEST </h2> <ol  style="color:#A7C7E7">
   
  <li>Stratify the data better (by LOB in particular) to better relect realistic scenarios</li>
  <li>Example - for commercial property setting the value of the individual site, use external data</li>

  <li>Not worthwhile spending time here Going between rpy2 (using Python in R, seperate notebooks for now) - Easier in Data bricks %R, %sql, %Python magic commands</li>
  <li>Include some outliers for testing (so can create a control table to flag or drop these fields)</li>


</ol> 

# Last Update - 2023/02/22

# Random_Data_Exploration
Generate random data - EDA it, model it, map it. Continual work in progress

Some of the Scripts in this can be run in the new CodeSpace feature

Random data is consists of these fields - will likely evolve to enrich the data
Geographic data - for example Latidues & Longitudes are randomly generated
  - then reverse geocoded to get the postcode
    - the open source version is new, very slow - many ways to break this down for example:
        - Break down the data set into seperate samples and run on different machines
          - Run time about 5 hours (average) for 10,000 random rows of lats & longs)
            - currently just random, so good luck finding a postcode in the Adriatic
            
Another appproach for generating REAL Postcodes is via python (check the script)
  - Currently only generates random postcodes for a few states in the US

Randomly Generated fields below

The link below creates random data based on criteria to generate random data, sample size is optional, simple logic for example you can't have a claim count where there was no conversion (sale) to begin with

The below is a generic random dataset for multiple lines of business 
  - work to be done here on the data sample - a claim for £200 for a phone is not the same as £2,000,000 for comercial property
[01_Create_Data](https://github.com/alexkotsscott/Random_Data_Exploration/blob/main/01_Create_Data.ipynb)

[01_Create_Data_Motor](https://github.com/alexkotsscott/Random_Data_Exploration/blob/main/01_Motor_Create_Data.ipynb)

"Customer_ID"
"Purchase_Date"
"Cover_Start_Date"
"LOB"
"Sale_Flag"
"Purchase_Price"
"Claims_Count"
"Period_of_Cover"
"Premium"
"Age"
"Broker"

