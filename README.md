# Data repository for R package [wru](https://github.com/kosukeimai/wru)

1. Spanish surname list from the Census ([spanish.csv](spanish.csv))
    - Data Description: A list of Spanish surnames identified by the Census
    - Data Source: [Florida Cancer Data System](https://fcds.med.miami.edu/downloads/DataAcquisitionManual/dam2018/26%20Appendix%20E%20Census%20List%20of%20Spanish%20Surnames.pdf) 
    
2. Merged surname list from the Census, supplemented by data from L2 voter files ([dict_last_merged.csv](dict_last_merged.csv))
    - Data Description: This is a list of U.S. surnames, along with the associated probabilities P(name | ethnicity) for ethnicities: white, Black, Hispanic, Asian, and other. The data is drawn from the census and supplemented by self-reported race data from L2 voter files for six states: Alabama, Florida, Georgia, Louisiana, North Carolina, and South Carolina.
    - Data Source: [U.S. Census API](https://api.census.gov/data/2010/surname?get=NAME,COUNT,CUM_PROP100K,PCT2PRACE,PCTAIAN,PCTAPI,PCTBLACK,PCTHISPANIC,PCTWHITE,PROP100K&RANK=1:200000) and data courtesy of [L2](https://l2-data.com/)
    
3. Surname list from L2 voter files only ([dict_last.csv](dict_last.csv))
    - Data Description: This is a list of U.S. surnames, along with the associated probabilities P(name | ethnicity) for ethnicities: white, Black, Hispanic, Asian, and other. The data is drawn from self-reported race data from L2 voter files for six states: Alabama, Florida, Georgia, Louisiana, North Carolina, and South Carolina.
    - Data Source: Data courtesy of [L2](https://l2-data.com/)


4. Middle name list from L2 voter files only ([dict_middle.csv](dict_middle.csv))
    - Data Description: This is a list of U.S. middle names, along with the associated probabilities P(name | ethnicity) for ethnicities: white, Black, Hispanic, Asian, and other. The data is drawn from self-reported race data from L2 voter files for six states: Alabama, Florida, Georgia, Louisiana, North Carolina, and South Carolina.
    - Data Source: Data courtesy of [L2](https://l2-data.com/)
    
5. First name list from L2 voter files only ([dict_first.csv](dict_first.csv))
    - Data Description: This is a list of U.S. first names, along with the associated probabilities P(name | ethnicity) for ethnicities: white, Black, Hispanic, Asian, and other. The data is drawn from self-reported race data from L2 voter files for six states: Alabama, Florida, Georgia, Louisiana, North Carolina, and South Carolina.
    - Data Source: Data courtesy of [L2](https://l2-data.com/)
    