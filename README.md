# Disaster
An android application which collects data (photos, safe areas info) from each phone connected to it and accumulates it to give a deeper information about the disaster hit area.

## Motivation
During the time of a disaster like flood, volcanic eruption etc where people are stuck in their homes and safe places, they are connected to the internet via their smartphones for a limited time during which they try to contact for help. During this time where people are stuck and are not able to do anything but wait, they need to make sure that their voices are heard and that people know their exact location details. One important factor for their rescue is that their surroundings are transformed due to the disaster and this modified map is unavailable to the rescue team.

## Solution
During the time people are stuck, they can contribute to the database which will help to get a deeper information about their surroundings. This can help them in getting their location information to the database to secure their rescue as well as contributes information of their surroundings so that the rescue team has a better understanding of the area.

### DataBase
Locality (approx 5000 sq. ft.) with attributes: safe sections, images, people in the locality, safety value (generated), last modified time.

### Input
Image template used to mark the safe parts of locality.  
![Locality info](https://raw.githubusercontent.com/sibby97/Disaster/master/images/area_layout.png "Locality info")
- Safe sections of the Locality. The sections are marked safe, unsafe or unknown.
- Other images of the area are also taken as input so that the rescuers are prepared for the search/rescue operation.
- The number of people in the area, to get an estimate of the people in the area.

## Assumptions
People have access to internet and they have their smartphones to use the application. This set of assumptions is applicable for disasters such as flood, volcanic eruption, acts of terrors, landslide, earthquake etc.
