# Europe-Covid-19-API
Cloud Computing Mini-Project: Group 15 

- Akhmet Saltanat ( student ID: 200819617, email: s.akhmet@se20.qmul.ac.uk )
- Gray Zac Anthony                 
- Holt John                         
- Obisesan Abayomi Olukayode
- Olubanjo Ashley

# API is for:
Data scientists, statisticians, developers, machines, programs, and other websites to be able to quickly fetch up to date culculated rates on the COVID-19 epidemic in specific European country and rigion.  This dynamically generated REST API with Flask and Python returns agregated and culculated monthly rates in EU countryies and rуgions based on live cases, vaccination, historical data. This can be used to build tools and systems that are used for advanced rates/ratios analysis and for European countries ranking building in public dashboards and charts.

#  Video on API: 
https://youtu.be/0cr2OLQw9zw

[![Video ](https://res.cloudinary.com/marcomontalbano/image/upload/v1617609265/video_to_markdown/images/youtube--0cr2OLQw9zw-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/0cr2OLQw9zw "Video")
# How to use API: 
- Cases data on specific country ( Example request:  Get /cases/United Kingdom )
- Cases data on specific country and region of that country ( Example request:  Get /cases/Germany/Bayern )
- Vaccines data on specific country ( Example request:  Get /vaccines/United Kingdom )
- Vaccines data on specific country and region of that country ( Example request:  Get /vaccines/Germany/Bayern )
- Deaths data on specific country ( Example request:  Get /deaths/United Kingdom )
- Deaths data on specific country and region of that country ( Example request:  Get /deaths/Germany/Bayern )
- Total deaths and death rate per 1000 population on specific country ( Example request:  Get /deaths/total/United Kingdom )
- Country with the most cases  (Example request:  Get /cases/most/United Kingdom )
- Country with the least cases (Example request:  Get /cases/least/United Kingdom )

# Data sources
- https://covid-api.mmediagroup.fr/v1
- https://github.com/M-Media-Group/Covid-19-API

