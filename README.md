# Ex04 Places Around Me
## Date: 31-03-24

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
<head>
<title>MY CITY</title>
</head>
<body>
<h1 align="center">
<font color="blue"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="green"><b>SWAMINATHAN V (212223110057)</b></font>
</h3>
<center>
    <img src="vellore.png" usemap="#image-map">

    <map name="image-map">
        <area target="" alt="Home Town" title="Home Town" href="static/hometown.html" coords="872,305,1154,487" shape="rect">
        <area target="" alt="Katpadi" title="Katpadi" href="static/katpadi.html" coords="1021,192,142" shape="circle">
        <area target="" alt="Ratnagiri" title="Ratnagiri" href="static/ratnagiri.html" coords="1423,372,1396,258,1244,346" shape="poly">
        <area target="" alt="Bagayam" title="Bagayam" href="static/bagayam.html" coords="907,623,1117,611,1086,504,1041,562,975,565,924,509,829,594" shape="poly">
        <area target="" alt="Usoor" title="Usoor" href="static/usoor.html" coords="689,572,812,545,761,618" shape="poly">
    </map>
</center>
</body>
</html>

<html>
<head>
<title>MY NATIVE</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="pink"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="green"><b>hometown</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="6">
    It is located about 137.20 kilometres (85 mi) west of Chennai, 
    and about 213.20 kilometres (132 mi) east of Bangalore. Vellore is located on the Mumbai–Chennai arm of the Golden Quadrilateral. Vellore is governed under a mayor and the Vellore Municipal Corporation. 

</font>
</p>
</body>
</html>

<html>
<head>
<title>MY NATIVE</title>
</head>
<body bgcolor="purple">
<h1 align="center">
<font color="black"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="green"><b>katpadi</b></font>
</h3>
<hr size="3" color="yellow">
<p align="justify">
<font face="Georgia" size="6">
    Katpadi is situated in the northern region of Vellore.
     It is home to prominent Vellore Institute of Technology (VIT) and also the famous Sri Lakshmi Narayani Golden Temple is 15km away.
</font>
</p>
</body>
</html>


<html>
<head>
<title>MY NATIVE</title>
</head>
<body bgcolor="white">
<h1 align="center">
<font color="black"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="pink"><b>Ratnagiri</b></font>
</h3>
<hr size="3" color="brown">
<p align="justify">
<font face="Georgia" size="6">
It is located at 16.98°N 73.3°E.[5] It has an average elevation of 11 meters (36 feet). 
The Sahyadri mountains border Ratnagiri to the east,it is the birthplace of Indian independence activist Lokmanya Tilak.[3] 
Thibaw, the last king of Burma, alongside his consort Supayalat and two infant daughters were exiled to a two-storied brick mansion in Ratnagiri.
</p>
</body>
</html>

<html>
<head>
<title>MY NATIVE</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="orange"><b>vellore</b></font>
</h1>
<h3 align="center">
<font color="green"><b>Bagayam</b></font>
</h3>
<hr size="3" color="white">
<p align="justify">
<font face="Georgia" size="6">
    A town of Bagayam, with the population of about 27,000 people, is a neighborhood town of Vellore, Tamil Nadu. 
    The local metropolitan area is one of the largest and the most crowded in northern Tamil Nadu. 
    The population is involved mainly in businesses related to mining, agriculture and commerce.


</p>
</body>
</html>

<html>
<head>
<title>MY NATIVE</title>
</head>
<body bgcolor="blue">
<h1 align="center">
<font color="orange"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="white"><b>Usoor</b></font>
</h3>
<hr size="3" color="green">
<p align="justify">
<font face="Georgia" size="6">
    Hosur is an industrial city located in Krishnagiri district in the Tamil Nadu state of India. Hosur is one of the 21 municipal corporations in Tamil Nadu. 
    It is located on the bank of the river River Ponnaiyar, 40 kilometres (25 mi) southeast of Bengaluru and 306 kilometres (190 mi) west of Chennai, the state capital.
</p>
</body>
</html>
```

## OUTPUT
![Screenshot 2024-03-31 222916](https://github.com/SwaminathanV23000747/NearMe/assets/148931113/59133543-b318-4c5a-899e-70ad66a6ea0f)

![Screenshot 2024-03-31 225952](https://github.com/SwaminathanV23000747/NearMe/assets/148931113/0ca45f8d-7294-45ea-b603-e2f219da5b5f)

![Screenshot 2024-03-31 225828](https://github.com/SwaminathanV23000747/NearMe/assets/148931113/88ae942d-2f3d-48e1-b752-e5e79ce269d3)
![Screenshot 2024-03-31 230012](https://github.com/SwaminathanV23000747/NearMe/assets/148931113/5d0de166-b004-4e73-aa0d-1334c06f4b20)
![Screenshot 2024-03-31 225850](https://github.com/SwaminathanV23000747/NearMe/assets/148931113/1de93f26-b55d-49ba-86f9-085febb9a61c)

![Screenshot 2024-03-31 230027](https://github.com/SwaminathanV23000747/NearMe/assets/148931113/c128c915-7cbe-4bcd-a274-45feff8e6631)





## RESULT
The program for implementing image maps using HTML is executed successfully.
