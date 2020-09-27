## Coursera: Applied Data Science Capstone 

### Introduction/Business Problem

Every year there are approximately 6 million car accidents in the US alone.  Car accidents are cause of the thousands of deaths and billions of dollars in expenses according to the US Car Accident statistics.
Analyzing the accident data in a major city like Seattle, may offer insights on car accidents in other major cities as well.
Goal is to understand this data to predict what factors lead to severity of accidents such as location, weather conditions, collision type etc.  Are there any factors we can educate the public to reduce the number of accidents.  Also, if find strong co-relation with certain weather conditions and severity of accidents, it may help to warn the drivers when faced with sthis situations.  This information can also be used to decide policies e.g. speed limit, closure of roads due to certain conditions etc.  Car insurance companies will also be interested to learn the insights from this data.  


### Data

Dataset is Seattle city collision data provided by the Seattle Police Department and recorded by Traffic Records.  It consists  ~194673 instances of collisions and ~38 attributes describing the event - severity of the accident, location, weather, collision type etc.  Collisions will be displayed at the intersection or mid-block of a segment. Timeframe of the data is 2004 to Present, thus it includes over 15 years of data that will help to see the trend over a decade.

This data will be explored to find what features most relevant to predict the severity of the accident.
 
Meta data to understand the attributes: https://s3.us.cloud-object-storage.appdomain.cloud/cf-courses-data/CognitiveClass/DP0701EN/version-2/Metadata.pdf

For example: SEVERITYCODE: A code that corresponds to the severity of the collision.

    3—fatality
    2b—serious injury
    2—injury
    1—prop damage
    0—unknown 