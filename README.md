# Ex04 Places Around Me
## Date: 16/12/2024

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
<img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="_blank" alt="Meni Kovil" title="Meni Kovil" href="temple.html" coords="773,164,636,93" shape="rect">
    <area target="_blank" alt="Madavamedu Beach" title="Madavamedu Beach" href="beach.html" coords="1034,268,75" shape="circle">
    <area target="_blank" alt="Silver Cascade Falls" title="Silver Cascade Falls" href="falls.html" coords="1449,74,1610,129" shape="rect">
    <area target="_blank" alt="Mosque sendurai" title="Mosque sendurai" href="mosque.html" coords="1205,447,90" shape="circle">
    <area target="_blank" alt="Aswins Home Special" title="Aswins Home Special" href="restaurant.html" coords="1062,714,1237,659" shape="rect">
</map>


beach.html
<html>
    <head>
        <title>My Home Town</title>

    </head>
    <body bgcolor="pink">
        <h1 allign="center">
            <font color="red"> <b>Ariyalur</b></font>

        </h1>
        <h3 allign="center">
            <font color="blue"> <b>Beach</b></font>
        </h3>
        <hr size="3" color="red">
        <p allign="justify">
            <font face="Georgia" size="5"></font>
        A beach is a narrow strip of land that borders a body of water,such as a lake or ocean
            </p>
            

    </body>
</html>

falls.html
<html>
    <head>
        <title>My Home Town</title>

    </head>
    <body bgcolor="pink">
        <h1 allign="center">
            <font color="red"> <b> Ariyalur</b></font>

        </h1>
        <h3 allign="center">
            <font color="blue"> <b>Falls</b></font>
        </h3>
        <hr size="3" color="red">
        <p allign="justify">
            <font face="Georgia" size="5"></font>
        A waterfall is a place in a river or stream where water flows over a steep drop or a series of steep drops
            </p>
            

    </body>
</html>

mosque.html
<html>
    <head>
        <title>My Home Town</title>

    </head>
    <body bgcolor="pink">
        <h1 allign="center">
            <font color="red"> <b> Ariyalur</b></font>

        </h1>
        <h3 allign="center">
            <font color="blue"> <b>Mosque</b></font>
        </h3>
        <hr size="3" color="red">
        <p allign="justify">
            <font face="Georgia" size="5"></font>
        "A mosque is a place of workship for muslims"
            </p>
            

    </body>
</html>

restaurant.html
<html>
    <head>
        <title>My Home Town</title>

    </head>
    <body bgcolor="pink">
        <h1 allign="center">
            <font color="red"> <b> Ariyalur</b></font>

        </h1>
        <h3 allign="center">
            <font color="blue"> <b>Restaurant</b></font>
        </h3>
        <hr size="3" color="red">
        <p allign="justify">
            <font face="Georgia" size="5"></font>
        "A restaurant is a place where you can sit down and relax,and let someone else do the cooking for you"
            </p>
            

    </body>
</html>

temple.html
<html>
    <head>
        <title>My Home Town</title>

    </head>
    <body bgcolor="pink">
        <h1 allign="center">
            <font color="red"> <b>Ariyalur</b></font>

        </h1>
        <h3 allign="center">
            <font color="blue"> <b>Temple</b></font>
        </h3>
        <hr size="3" color="red">
        <p allign="justify">
            <font face="Georgia" size="5"></font>
        A temple is a building where people workship gods or engage in other religious activities
            </p>
            

    </body>
</html>
```


## OUTPUT


![alt text](<Screenshot (6).png>)
![alt text](<Screenshot (5).png>)
![alt text](<Screenshot (4).png>)
![alt text](<Screenshot (3).png>)
![alt text](<Screenshot (2).png>)
![alt text](<Screenshot (1).png>)



## RESULT
The program for implementing image maps using HTML is executed successfully.
