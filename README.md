# Ex04 Places Around Me
## Date:  25/4/25

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

~~~
<html>
    <head>
        <title>image Map</title>
    </head>
    <body>
        <div id="container">
        <center>
        <div id="image_container">
        <h1>FAMOUS TEMPLES IN TAMILNADU</h1>
         <br><img src="maps.jpg" usemap="#image-map">
         <h2> Find in Google map</h2>
        </div>
        </center>

    <map name="image-map">
        <area shape="poly" coords="246,80,329,77,238,117,348,113" title="namma ooru" href="page1.html">
        <area shape="poly" coords="164,279,240,268,163,319,232,319" title="enga ooru" href="page4.html">
        <area shape="poly" coords="56,188,134,195,42,224,140,228" title="harini ooru" href="page2.html">
    </map>
    </div>
    </div>
    </body>
</html>
```

```
<html>
    <head>
            <title>THIRUVANNAMALAI TEMPLE</title>
            <center><h1>THIRUVANNAMALAI TEMPLE</h1></center><BR><br>
            <center>
            <img src="tvmtemple.webp"><br><br>
            </center>
            <center>
            <h2>Thiruvannamalai Temple,also known as Arunachaleswarar Temple<br>It  is scared Hindhu temple  dedicated to lord shivan. It is one of a pancha Bhoota stalams, Representing the element of fire 
                Temple  features a massive shiva lingsam , over 10n Feet tall , made black granite . The temple has nine impressive gopurams with the eastern  gopuram being the tallest one(127 feet) .The temple is adorned with intricate cravings cculptures depicting Hindu mythology. The temple is associated with the revered saint ramana maharshi, who spent many years mediating in the templ
                there are four main goupuram.Thiruvannamalai is considered as a powerful spiritual center , attracting devotes and seekers from worldwide. There is more interesting facts about Arunachaleswarar temple.
            </h2>
            </center>
    </head>
    <body style="background-color:beige;">
        <style>
            h1,h2{
                font-family:Georgia, 'Times New Roman', Times, serif ;
                font-size:x-large ;
                font-style:italic;
                color:black;
            }
        </style>
    </body>
</html>
```

```
<html>
    <head>
        <title>COIMBATORE TEMPLE</title>
        <style>

        </style>
        <center><h1>COIMBATORE TEMPLE</h1></center><br><br>
        <center>
            <img src="ishaa.jpg"><br><br><br>
        </center>
        <center>
            <h2><p style=" text-align: center;"><br>Main center in coimbatore offers various yoga program, meditation, spiritual retreat A scared 
                <br>Imeditation shrine,  the Dhyanalinga is a powerful tool for spirtual growth and self-transformation.  
                <br>The foundation has installed a massive statue of Adiyogi Shiva, which is symbol of spiritual growth 
                <br>and self-transformation. A rural education intiative, Isha Vidya provides quality education to 
                <br>underprivileged children. An environmental initivative , Project GreenHands aims to plant 114 million
                <br>trees in Tamil Nadu.A cultural wing promoting classical arts, music,and literature. To know more interesting
                <br>things about adiyoga go and visit.</p>
            </h2>
        </center>
    </head>
    <body style="background-color:beige;">
        <style>
            h1,h2{
                font-family:Georgia, 'Times New Roman', Times, serif ;
                font-size:x-large ;
                font-style:italic;
                color:black;
            }
        </style>
</html>
```
```
<html>
    <head>
        <title>MADURAI TEMPLE</title>
        <center><h1>MADURAI TEMPLE</h1></center><br><br>
        <center>
            <img src="mtewmp.jpg"><br><br>
        </center>
        <center>
            <h2>
            the temple it as roots in the 1st centuryCE,with the current structure dating back to the 16th centuryCE.
            The temple is known for stunning Dravidian  archetecture , featuring  intricate cravings, goupuram and mandapam.
            The temple is dedicated to goddess madurai meenakshi, a form of parvati, who is worshipped as the primary deity.  
            Lord Shiva is also worshipped in the temple as Sundareshwar.The temple has a scared tank called the "potramarai kulam"
            The temple celebrate  various festivals throughtout the year,including the famous "Meenakshi Thirukalyanam".The temple
            was witnessed various historical events and has been ruled by different dynasties.The temple features beautiful sculptures
            and cravings showcase the artistic skills of ancient craftsmen. </h2>
        </center>
    </head>
    <body style="background-color:beige;">
        <style>
            h1,h2{
                font-family:Georgia, 'Times New Roman', Times, serif ;
                font-size:x-large ;
                font-style:italic;
                color:black;
            }
        </style>
</html>
~~~

## OUTPUT


![image](https://github.com/user-attachments/assets/4f6f4242-6289-441e-8af6-e1b8501d866d)


![image](https://github.com/user-attachments/assets/98829026-a98a-4769-87e8-cd427937ddbe)


![image](https://github.com/user-attachments/assets/e4e2d62f-341d-46a2-9e5b-5b71b19e0193)


![image](https://github.com/user-attachments/assets/ae43099b-08fd-456d-a911-9f18c16a4f77)


## RESULT


The program for implementing image maps using HTML is executed successfully.

