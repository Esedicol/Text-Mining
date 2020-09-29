# Text Mining (Date)

Given a csv file containing medical records find and retrieve only the date in every row. The records will have a variety of dates i.e:
- day/month - missing year value
- month/year - missing day value 
- day/month/year, month, day, year
- month can either be in words or number.
- 04/02/2009 (day, month, year)
- Mar 2 2009 (month, day, year)
- Feb 2009 (_, month, year)
- 2009 (, , year)

Note: 
- any missing month will be replaced by 1 and any missing year will be replace by 2020.
- the final extracted date should be in the following format (month/day/year)

Aims:
- use regular expressions to extract date
- perform cleaning of massage because some months are spelled wrong


