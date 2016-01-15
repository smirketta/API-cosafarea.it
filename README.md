# API-cosafarea.it
Public APIs for retrieving content from the website cosafarea.it. 

These APIs offer the possibility to retrieve infos related to turistic sites.

<h2>How to use cosafarea.it API</h2>

<b>Url: </b>
<p>http://cosafarea.it/api/cosafarea_api.php</p>
<hr>

<b>Parameters: </b>
<ul>
<li>address -> city you want to retrieve info of</li>
<li>category -> type of attractions</li>
<li>limit -> number of attractions, on default all attractions</li>
</ul>
<hr>

<b>List of categories: </b>
<ul>
<li>chiese</li>
<li>divertimenti</li>
<li>luoghi-di-interesse</li>
<li>monumenti</li>
<li>musei</li>
<li>parchi-e-natura</li>
<li>piazze</li>
<li>ristoranti</li>
<li>pub</li>
<li>all -> all the categoris listed above</li>
<li>attrazioni -> include all these categories [chiese, divertimenti, luoghi-di-interesse, monumenti, musei, parchi-e-natura, piazze] </li>
</ul>
<hr>
<b>Examples:</b>

<p>http://cosafarea.it/api/cosafarea_api.php?address=roma&category=ristoranti&limit=2
<br/>
It displays the first 2 restaurants in Rome ordered by date of publication</p>
<p>
http://cosafarea.it/api/cosafarea_api.php?address=roma&category=ristoranti,pub
<br/>
<p>
All the restaurants and pubs in Rome
</p>
