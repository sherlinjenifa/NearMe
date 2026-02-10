# Ex03 Places Around Me
## Date: 10.02.2026

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE
```
map.html

<html>
    <head>
       <title>Kanniyakumari map</title> 
    </head>
    <body>
        <h3>Kanniyakumari</h3>
        <h4>Sherlin Jenifa VS  25017634</h4>
        <img src="Screenshot 2026-02-09 104623.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Mathoor Aqueduct" title="Mathoor Aqueduct" href="Mathoor.html" coords="716,616,917,692" shape="rect">
    <area target="" alt="Kaalikesam Waterfalls" title="Kaalikesam Waterfalls" href="kaali.html" coords="986,385,99" shape="circle">
    <area target="" alt="Pechiparai dam" title="Pechiparai dam" href="Pechiparai.html" coords="662,168,732,163,787,192,792,241,749,264,671,266,632,233,625,196" shape="poly">
    <area target="" alt="Nambi kovil falls" title="Nambi kovil falls" href="nambi.html" coords="1302,274,1489,317" shape="rect">
    <area target="" alt="Kuthara Paanjan Waterfalls" title="Kuthara Paanjan Waterfalls" href="kuthara.html" coords="1547,566,78" shape="circle">
</map>
    </body>
</html>

kaali.html

<html>
    <head>
        <title>Kanniyakumari - Mathoor</title>
    </head>
    <body bgcolor="yellow">
        <h1 bgcolor="Red" align="center">kanniyaKumari - Kumari City</h1>
        <h3 bgcolor="Blue" align="center">Kaalikesam waterfalls</h3>
        <p>Kaalikesam waterfalls, located in kanniyakumari district within the keeriparai wildlife sanctuary ,is a serene, lesser-known spot featuring a scenic river stream surrounded by dense forests, situated near a historic temple to lord </p>
    </body>
</html>

kuthara.html

<html>
    <head>
        <title>Kanniyakumari - Pechiparai</title>
    </head>
    <body bgcolor="purple">
        <h1 align="center">kanniyaKumari - Kumari City</h1>
        <h3 align="center">Kuthara Paanjan Waterfalls</h3> 
        <p>Kuthara Paanjan Waterfalls (or Panagudi Falls) is a 150-foot cascading waterbody located in the scenic Western Ghats near Panagudi in Tamil Nadu’s Tirunelveli district</p>
    </body>
</html>

Mathoor.html

<html>
    <head>
        <title>Kanniyakumari - kaali</title>
    </head>
    <body bgcolor="Pink">
        <h1 align="center">kanniyaKumari - Kumari City </h1>
        <h3 align="center">Mathoor aquaedate</h3>
        <p>The mathoor adequate located in kanniya kumari district is the tallest and longest trough bridge in Asia,standing at 115 feet high and 1 km long constructed in 1966 acress the river parazhiyar</p>
    </body>
</html>

nambi.html

<html>
    <head>
        <title>Kanniyakumari - Pechiparai</title>
    </head>
    <body bgcolor="orange">
        <h1 align="center">kanniyaKumari - Kumari City</h1>
        <h3 align="center">Nambi kovil falls</h3> 
        <p>Nambi Kovil Falls, located near the
Tirunelveli-based Malai Nambi Temple in the Western Ghats, is a serene natural cascade set within lush surroundings. Known for its refreshing waters, this site offers a scenic, trekking-friendly experience for pilgrims visiting the nearby hilltop temple. 
</p>
    </body>
</html>

Pechiparai.html

<html>
    <head>
        <title>Kanniyakumari - Pechiparai</title>
    </head>
    <body bgcolor="orange">
        <h1 align="center">kanniyaKumari - Kumari City</h1>
        <h3 align="center">pechiparai dam</h3>
        <p>Located in the Western Ghats of Kanyakumari district, Tamil Nadu, the Pechiparai Dam is a major reservoir built across the Kodayar River between 1897 and 1906 by British engineer Mr. Minchin. It is the largest dam in the district, serving as a crucial source for irrigation and drinking water while offering a scenic tourist spot. </p>
    </body>
</html>


```


## OUTPUT
![alt text](<Screenshot (26).png>) 
![alt text](<Screenshot (27).png>) 
![alt text](<Screenshot (28).png>)
![alt text](<Screenshot (29).png>) 
![alt text](<Screenshot (30).png>) 
![alt text](<Screenshot (31).png>)






## RESULT
The program for implementing image maps using HTML is executed successfully.
