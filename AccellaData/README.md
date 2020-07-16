This part of the project brings in housing habitability data from the Oakland Accela database: https://aca.accela.com/OAKLAND/Welcome.aspx

Steps:
1) bring in data (csv) from 2016-2018 from the housing habitability complaint database (note: need to check if any of the others are worth searching)
2) create new variables that flag existance in the description of any original complaint or closed complaint (which will exclude follow up visits, although need to confirm this) any of the following words: mold, mildew, water, leak, plumbing, moist, seepage, black, ventilation, flood, rot, condensation, corroded, and mildrew (mispelling)
3) prepare data for geographic analysis by geocoding (see office hours discussion of this for directions)

bonus:
4) create function that downloads the data automatically from the website and provides all the records that include a user defined keyword
