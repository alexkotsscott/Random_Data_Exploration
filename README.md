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

[https://github.com/alexkotsscott/Random_Data_Exploration/blob/main/01_Create_Data.ipynb](other_file.md)

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

