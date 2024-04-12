# Exploring-London-s-Travel-Network
London, or as the Romans called it "Londonium"! Home to over 8.5 million residents who speak over 300 languages. While the City of London is a little over one square mile (hence its nickname "The Square Mile"), Greater London has grown to encompass 32 boroughs spanning a total area of 606 square miles! Given the city's roads were originally designed for horse and cart, this area and population growth has required the development of an efficient public transport system! Since the year 2000, this has been through the local government body called Transport for London, or TfL, which is managed by the London Mayor's office. Their remit covers the London Underground, Overground, Docklands Light Railway (DLR), buses, trams, river services (clipper and Emirates Airline cable car), roads, and even taxis.

The Mayor of London's office make their data available to the public [here](https://data.london.gov.uk/dataset). The Mayor would like to find out the following basic questions regarding the use of London's public transportation network:

#### 1) What are the popular transportation types, measured by total number of journeys?
#### 2) In which 5 months and years did Emerates Airlines have the most business?
#### 3) Which 5 years had the lowest volume of Underground and DLR journeys?

### The Dataset
TFL.JOURNEYS

| Column | Definition | Data type |
|--------|------------|-----------|
| `MONTH`| Month in number format, e.g., `1` equals January | `INTEGER` |
| `YEAR` | Year | `INTEGER` |
| `DAYS` | Number of days in the given month | `INTEGER` |
| `REPORT_DATE` | Date that the data was reported | `DATE` |
| `JOURNEY_TYPE` | Method of transport used | `VARCHAR` |
| `JOURNEYS_MILLIONS` | Millions of journeys, measured in decimals | `FLOAT` |

## The Analysis
### What are the most popular transport types, measured by total number of journeys?
![Screenshot (2)](https://github.com/bhammy27/Exploring-London-s-Travel-Network/assets/154477061/2e5918ee-fdf4-421e-832b-0a879b4d8147)

There is no surprise that Bus transportation leads the list. Who can resist riding a Red Double decker bus when in London. The ease of use and numerous Tube stations around town makes the Underground & DLR the second most popular form of public transportation.

### In which 5 months and years did Emerates Airlines have the most business?
![Screenshot (3)](https://github.com/bhammy27/Exploring-London-s-Travel-Network/assets/154477061/d1a67065-83dc-4a07-b048-1e59ff5ae7c1)

London was a popular destination in 2012. The city hosted the Summer Olympics from late July to mid-August. It is interesting that Emirates Airlines had their most trips in the 3 months leading up to the Olympics and not the months during or months after the Olympics.

### Which 5 years had the lowest volume of Underground & DLR journeys
![Screenshot (4)](https://github.com/bhammy27/Exploring-London-s-Travel-Network/assets/154477061/a65c65b3-6372-4e4d-abd5-71a7c6ffadb7)


It makes perfect sense that in 2020, and the following years after, the Underground & DLR would have its lowest usage.

