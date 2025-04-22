# Ex04 Places Around Me
## Date: 22/04/2025

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
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Sankarankovil</b></font>   
</h1>  
<h3 align="center">
<font color="blue"><b>Arunkumar S (212224230024)</b></font>    
</h3> 
<center>
<img src="map.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="700,250,900,900" href="home.html" title="My Home Town">
<area shape="rect" coords="50,50,150,150" href="Hospital.html" title="Razak Hospital">
<area shape="circle" coords="300,200,50" href="phone.html" title="Poorvika Mobiles Sankarankoil">
<area shape="poly" coords="400,100,450,150,420,200" href="Theater.html" title="Movie Theater">
<area shape="rect" coords="200,300,300,350" href="Bus Stand.html" title="New Bus Stand">
<area shape="poly" coords="600,250,650,300,620,350" href="Street.html" title="Lakshmiyapuram">

</map>    
</center> 
</body>
</html>

phone.html

<!DOCTYPE html>
<html>
<head>
    <title>Poorvika Mobiles - Sankarankoil</title>
</head>
<body>
    <h1>Poorvika Mobiles - Sankarankoil</h1>
    <p><strong>Location:</strong> No: 187, Rajapalayam Main Road, Opp. Assembly Lodge, Sankarankoil, Tamil Nadu 627756</p>
    <p><strong>Contact:</strong> <a href="tel:+914443666666">Call: +91 44 4366 6666</a></p>
    <p><strong>Website:</strong> <a href="https://www.poorvika.com/">Poorvika Official Site</a></p>

    <h2>Products & Services</h2>
    <ul>
        <li>Smartphones (Apple, Samsung, OnePlus, Xiaomi, etc.)</li>
        <li>Laptops & Accessories</li>
        <li>Smart TVs & Audio Devices</li>
        <li>Mobile Repairs & Services</li>
    </ul>

    <h2>Find Us on Google Maps</h2>
    <iframe src="https://maps.google.com/?q=Poorvika+Mobiles+Sankarankoil" width="600" height="450"></iframe>
</body>
</html>
```


## OUTPUT
![alt text](<Screenshot 2025-04-22 120411.png>)
![alt text](<Screenshot 2025-04-22 120432.png>)





## RESULT
The program for implementing image maps using HTML is executed successfully.
