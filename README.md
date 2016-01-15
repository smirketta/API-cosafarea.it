# API-cosafarea.it
Public APIs for retrieving content from the website cosafarea.it. 

These APIs offer the possibility to retrieve infos related to turistic sites.

How to use cosafarea.it API.

Url: 
http://cosafarea.it/api/cosafarea_api.php

Parameters: 
address -> city you want to retrieve info of
category -> type of attractions
limit -> number of attractions, on default all attractions

Possible categories are: 

chiese
divertimenti
luoghi-di-interesse
monumenti
musei
parchi-e-natura
piazze
ristoranti
pub
all -> all the categoris listed above
attrazioni -> include all these categories [chiese, divertimenti, luoghi-di-interesse, monumenti, musei, parchi-e-natura, piazze] 

Examples:

http://cosafarea.it/api/cosafarea_api.php?address=roma&category=ristoranti&limit=2

It displays the first 2 restaurants in Rome ordered by publishing date

http://cosafarea.it/api/cosafarea_api.php?address=roma&category=ristoranti,pub

All the restaurants and pubs in Rome
