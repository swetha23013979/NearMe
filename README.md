# Ex04 Places Around Me
## Date: 

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE

```

<html>
    <title>Mycity</title>
    <body bgcolor="white">
        <h1 align="center"><font color="black"></font></h1>
        <h3 align="center">
            <font color="blue"></font></h3>
        <center>
            <img src="map.png"  usemap="#MyCity" height="550" width="1300">
            <map name="MyCity">
                    <area shape="rect" coords="750,50,250,200" href="Temple.html" title="Sri Vijaya Ganapathi Alayam">     
                    <area shape="rect" coords="0,0,0,0" href="Falls.html" title="Perandapalli Forest Water Falls">
                    <area shape="rect" coords="850,50,150,05" href="Dam.html" title="Kelavarapalli Dam">
                    <area shape="rect" coords="750,150,250,200" href="Museum.html" title="Rajaji Memorial House">
                    <area shape="rect" coords="80,0,0,0" href="Hotel.html" title="Hotel Hills">
            </map>
        </center>

    </body>
</html>

Temple.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">krishnagiri</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="red" size="5.5">Sri Vijaya Ganapathi Alayam</font>
    </h3>
    <body bgcolor="pink" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            With Sri Vijaya Ganapathi Swamy's Grace, the village worshipers have experienced grand successes in their undertakings. Devotees are bestowed with health, wealth and content. Sri Ganapathi being the Deity of Wisdom ( Buddhi Devatha), student devotees are blessed with excellence in their education.Focusing on spiritual aspect, MaSS has initiated into renovating temples in the village. Since 1984, Vinayaka Chaturthi celebrations and Daily Pooja's are performed in Sri Vijaya Ganapathi temple, Muchivolu. There is a strong belief that Health, Education & Agricultural activities in the village have improved significantly by the blessings of Lord Vijaya Ganapathi.
        </font>
        </p>
    </body>
</html>

Falls.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">krishnagiri</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="red" size="5.5">Perandapalli Forest Water Falls</font>
    </h3>
    <body bgcolor="blue" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            The joy of travel comes in exploring new things. Planting your feet somewhere you have never been before brings with it the rush of discovery and the joy of pushing back on the boundaries of your world.
        </font>
        </p>
    </body>
</html>

Dam.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">krishnagirir</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="red" size="5.5">Kelavarapalli Dam</font>
    </h3>
    <body bgcolor="purple" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Kelavarapalli dam is constructed in thenpennai river which originates from Nandi hills and ends at bay of Bengal.A small dam where you won't see much attractions around it, you can walk over the dam to see the reservoir and water discharge area.
        </font>
        </p>
    </body>
</html>

Museum.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">Krishnagiri</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="red" size="5.5">Rajaji Memorial House</font>
    </h3>
    <body bgcolor="violet" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Birthplace & former house of Chakravarti Rajagopalachari.This is the house where Chakravarti Rajagopalachari was born and spent his childhood. He was India's last Governor-General.
        </font>
        </p>
    </body>
</html>

Hotel.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">krishnagiri</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="red" size="5.5">Hotel Hills</font>
    </h3>
    <body bgcolor="cyan" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            The Hotel Hills, Hosur offers a clean and quiet place to begin and end your day with its unbeatable value and reliable safety standards.
        </font>
        </p>
    </body>
</html>

```

## OUTPUT

![Screenshot 2024-05-12 155534](https://github.com/swetha23013979/NearMe/assets/153823422/8f3350dd-d366-4ac4-8a83-11c20a90c183)

![Screenshot 2024-05-12 155554](https://github.com/swetha23013979/NearMe/assets/153823422/1029b8c3-6365-45c8-87cf-b0cc2615c3ff)


![Screenshot 2024-05-12 155609](https://github.com/swetha23013979/NearMe/assets/153823422/111bb30c-644e-4831-b11d-71d79a655341)

![Screenshot 2024-05-12 155629](https://github.com/swetha23013979/NearMe/assets/153823422/f053f8c5-76c6-4a1d-989e-14527ca98372)

![Screenshot 2024-05-12 155645](https://github.com/swetha23013979/NearMe/assets/153823422/8208dc60-7e30-417e-badf-d9d2b4097b63)


![Screenshot 2024-05-12 155657](https://github.com/swetha23013979/NearMe/assets/153823422/d36be835-85aa-4fdd-96d5-cb11f3cb31ee)


## RESULT
The program for implementing image maps using HTML is executed successfully.
