# Ex04 Places Around Me
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
# MAP.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"MAP"</title>
    <h1 align="center">
        <font color="blueS" face="cursive">
           SANTHOSH L 212222100046- MAP 
        </font>
    </h1>
</head>
<body>
    <img src="/static/map.png" usemap="#image-map">

    <map name="image-map">
        <area target="_blank" alt="BUS STAND" title="BUS STAND" href="bus.html" coords="517,371,699,425" 
shape="rect">
        <area target="_blank" alt="MAPS" title="MAPS" href="market.html" coords="141,497,337,419" shape="rect">
        <area target="_blank" alt="MY HOME " title="MY HOME" href="home.html" coords="827,309,607,173" shape="rect">
        <area target="_blank" alt="THEATRE" title="THEATRE" href="theatre.html" coords="47,93,245,-1" shape="rect">
        <area target="_blank" alt="TEMPLE" title="TEMPLE" href="temple.html" coords="433,299,204,177" shape="rect">
    </map>
</body>
</html>
```
# BUS.HTML
```
<h1 align="center">
    <font color="blueS" face="cursive">
        BUS STAND
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        <OL  TYPE="1" START="1">
            <LI> This is a very popular bus stand in chennai.<br></LI>     
            <LI> its one of chennai's biggest bus stand.<br></LI>
            
        </OL>


    </font>
    <font color ="blue" face = "cursive" size="20" > 
    "MOST POPULAR BUS STAND"
    </font>
```
# HOME.HTML
```
<h1 align="center">
    <font color="purple" face="cursive">
        MY HOME
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        <OL  TYPE="1" START="1">
            <LI>This is where i live.<br></LI>     
            <LI>my home is always the best place .<br></LI>
            <LI>and the view from my house is just spectacular.<br></LI>
            
        </OL>


    </font>
    <font color ="purple" face = "cursive" size="20" > 
    "HOME WILL ALWAYS BE HOME"
    </font>
```
# MARKET.HTML
```
<!DOCTYPE html>
<html>
<head>
    <title>
        MARKET
    </title>
</head>
<body bgcolor="red">
<h1 align="center">
    <font color="green"face="Road" size="30">
        
    </font>
</h1>
<p align="center">
    <font color="yellow" face="stretch" size="24">
            <LI>this is the area where we get all the needed vegetable,fruits,flowers,etc.
    </font>
</p>
</body>
</html>
```
# THEATRE.HTML
```
!DOCTYPE html>
<html>
<head>
    <title>
        THEATRE
    </title>
</head>
<body bgcolor="premium">
<h1 align="center">
    <font color="silver" face="body">
        THEATRE
    </font>
</h1>
<p align="center">
    <font color="black" face="Comic Sans MS" size="24">
        <OL  TYPE="1" START="1">
            <LI>A place where everyone enjoys wacthing a movie.<br></LI> 
        </OL>
    </font>
    <font color ="red" face = "cursive" size="16" > 
    "A theatre always entertains."
    </font>
</p>
</body>
</html>
```
# TEMPLE.HTML
```
<h1 align="center">
    <font color="blueS" face="cursive">
        TEMPLE
    </font>
</h1>
<p align="center">
    <font color="red" face="Comic Sans MS" size="24">
        <OL  TYPE="1" START="1">
            <LI>this is a very auspicious place,where everyone workships god.<br></LI>     
            <LI>Its one of the most famous temples in chennai.<br></LI>
            
        </OL>


    </font>
    <font color ="blue" face = "cursive" size="20" > 
    "Temple Is A Place Of Peace"
    
    
    </font>
```

## OUTPUT
![Alt text](<Screenshot (49).png>)
![Alt text](<Screenshot (50).png>)
![Alt text](<Screenshot (51).png>)
![Alt text](<Screenshot (52).png>)
![Alt text](<Screenshot (53).png>)
![Alt text](<Screenshot (54).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
