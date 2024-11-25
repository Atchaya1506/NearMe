# Ex04 Places Around Me
## Date:25/11/2024

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
map.html
<html>
<head>
<title>My Dharmapuri</title>
</head>
<body>
<h1 align="center">
<font color="violet"><b>Dharmapuri</b></font>    
</h1>
<h3 align="center">
<font color="blue"><b>Atchaya B (24900268)</b></font>    
</h3>
<center>
    <img src="map.png" usemap="#MyDharmapuri">
    
    <map name="MyDharmapuri">
        <area target="" alt="DNC" title="DNC" href="DNC.html" coords="427,109,631,174" shape="rect">
        <area target="" alt="Hospital" title="Hospital" href="Hospital.html" coords="745,128,920,196" shape="rect">
        <area target="" alt="Mandapam" title="Mandapam" href="Mandapam.html" coords="513,573,742,657" shape="rect">
        <area target="" alt="Zudio" title="Zudio" href="Zudio.html" coords="602,196,753,259" shape="rect">
        <area target="" alt="Clinic" title="Clinic" href="Clinic.html" coords="569,385,730,476" shape="rect">
</map>    
</center>
</body>
</html> 

Clinic.html
<html>
<head>
<title>My Dharmapuri</title>
</head>
<body bgcolor="red">
<h1 align="center">
<font color="violet"><b>Dharmapuri</b></font>    
</h1>
<h3 align="center">
<font color="blue"><b>Clinic</b></font>    
</h3>
<hr size="3" color="blue">
<p align="justify">
<front face="Georgia" size="S">
Government Dharmapuri Medical College is located in Dharmapuri, Tamil Nadu. It is a premier institute in higher education and offers Degree courses including UG and PG Programmes.The most popular programmes offered at the government Dharmapuri Medical College are MBBS. 
<p>
</body>
</html>

DNC.html
<html>
<head>
<title>My Dharmapuri</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="violet"><b>Dharmapuri</b></font>    
</h1>
<h3 align="center">
<font color="blue"><b>DNC</b></font>    
</h3>
<hr size="3" color="gray">
<p align="justify">
<front face="Georgia" size="S">
It is located in Dharmapuri Bazar street Dharmapuri.Despite the location.it provide a cinematic experience suited for multiplexes in the city with its amenities and technology.It includes three floors including cinema theatre (five screens),cantten facility and car parking facilities.
<p>
</body>
</html>

Hospital.html
<html>
<head>
<title>My Dharmapuri</title>
</head>
<body bgcolor="gray">
<h1 align="center">
<font color="violet"><b>Dharmapuri</b></font>    
</h1>
<h3 align="center">
<font color="blue"><b>Hospital</b></font>    
</h3>
<hr size="3" color="blue">
<p align="justify">
<front face="Georgia" size="S">
Jothi Eye Care Hospital is a global leader in opthalmology has stood at the forefront of eye care since 1948. Our world-class team of eye care specialist is committed to providing you the greatest level of eye care servieces.We have the expertise of treating the rarest symptoms to performing the most complicated surgeries.
<p>
</body>
</html>

Mandapam.html
<html>
<head>
<title>My Dharmapuri</title>
</head>
<body bgcolor="indigo">
<h1 align="center">
<font color="violet"><b>Dharmapuri</b></font>    
</h1>
<h3 align="center">
<font color="blue"><b>Mandapam</b></font>    
</h3>
<hr size="3" color="blue">
<p align="justify">
<front face="Georgia" size="S">
Madhutabhai Sundar Rao Kalyana Mandapam in Bharathipuram,Dharmapuri listed under Mondap Decorators in Dharmapuri.Rated 4.1 based on 622 customer  reviews.It is placed near Salem main road Bharathipuram,dharmapuri Tamil Nadu.   
<p>
</body>
</html>

Zudio.html
<html>
<head>
<title>My Dharmapuri</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="violet"><b>Dharmapuri</b></font>    
</h1>
<h3 align="center">
<font color="blue"><b>Zudio</b></font>    
</h3>
<hr size="3" color="yellow">
<p align="justify">
<front face="Georgia" size="S">
Zudio is a fashion retail brand from the house of Tata Groups retail arm,Trent limited.It is owned by Trent Limited,which in turn belongs to the Tata Group.Founded by Jamshedji,the then chairman of tata group ratan N tata,Trents early focus was on retail operations.Their collections boast of high-quality fabrics,comfortable fits,and eye catching designs ensuring customer feel confident and stylish in every outfit
<p>
</body>
</html>
```

## OUTPUT
![alt text](1-1.png)
![alt text](2-1.png)
![alt text](3-1.png)
![alt text](4-1.png)
![alt text](5-1.png)
![alt text](6-1.png)






## RESULT
The program for implementing image maps using HTML is executed successfully.
