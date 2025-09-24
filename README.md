# Ex04 Places Around Me
## Date: 24.08.2025

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
        <title>Vellore City</title>
    </head>
    <Body>
        <h2>Shreeshanth <br> Ref_no.:25012265</h2>
        <img src="Screenshot 2025-09-20 142218.png" usemap="#image-map">

        <map name="image-map">
            <area target="" alt="Vellore Fort" title="Vellore Fort" href="fort.html" coords="611,426,42" shape="circle">
            <area target="" alt="Tipu and Haider Mahal" title="Tipu and Haider Mahal" href="mahal.html" coords="469,431,543,496" shape="rect">
            <area target="" alt="Sajra Fort" title="Sajra Fort" href="sajra.html" coords="1226,248,1258,221,1292,232,1307,267,1285,305,1231,296" shape="poly">
            <area target="" alt="Government Museum" title="Government Museum" href="museum.html" coords="645,510,644,489,622,484,604,498,608,517,630,525" shape="poly">
            <area target="" alt="Gojra Fort" title="Gojra Fort" href="gojra.html" coords="1265,591,55" shape="circle">
        </map>
    </Body>
</html>

fort.html
<html>
    <head>
        <title>Vellore Fort</title>
    </head>
    <body bgcolor="99FFFF">
        <h2 align="center"><u> VELLORE FORT </u></h2>
        <p align="justify" style="font-size: larger;">
        The Fort was constructed by then the ruler Bommu Nayakar and his brother during 1526-1595 AD
        <br><br>
        The First Mutiny against the British in India broke out in Vellore Fort (1806 – Sippoy Kalagam)Tippu Mahal, Hyder Mahal, Condy Mahal, Badhusha Mahal and the Begam Mahal in side the Fort.The fort at Vellore is one of the great attractions in the District. It is Said to have been built by Chinna Boomi Nayaka a subordinate under Sadasivaraya of the Vijayanagara Kindom in mid of 16th Century A.D. The fort was occupied by the British in 1760 and used as a military garrison. The rectangular fort with a circumference of 3km is built entirely with massive granite cut stones.The fort contains both secular and religious structures including tippu Mahal, Begum Mahal, Kandi Mahal, Jalakanteswara Temple, A mosque and a Church Museums also established by 01, April 1999 in this fort by the Archaeological Survey of India and State Department.
        </p>
    </body>
</html>

museum.html
<html>
    <head>
        <title>Governement Museum</title>
    </head>
    <body bgcolor="FFFF99">
        <h2 align="center"><u>GOVERNMENT MUSEUM</u></h2>
        <p align="justify" style="font-size: larger;">
            The Government Museum in Vellore is a multipurpose museum located within the historic Vellore Fort. Established in 1985, the museum preserves and showcases the art, history, archaeology, and culture of the region, specifically the former North Arcot District (now Vellore and Tiruvannamalai). 
        </p>
    </body>
</html>

gojra.html
<html>
    <head>
        <title>Gojra Fort</title>
    </head>
    <body bgcolor="99FF99">
        <h2 align="center"><u>GOJRA FORT</u></h2>
        <p align="justify" style="font-size: larger;">
        Gojra Fort is one of two hilltop fortifications built by Chhatrapati Shivaji Maharaj near Vellore in 1678 to strategically bombard and capture Vellore Fort, which was being defended by the Bijapur army. Located on Naammam Malai hill with the Sajra Fort, Gojra Fort's name means "cute" in Marathi and it helped the Marathas to win the siege, leading to their control of Vellore for the next 30 years.  
Key aspects of Gojra Fort:
Purpose: It was a temporary but strategically vital fort built to gain a vantage point for bombarding the main Vellore Fort. 
Builder: Chhatrapati Shivaji Maharaj ordered its construction. 
Historical Context: The fort was built during the Maratha siege of Vellore in 1678, lasting fourteen months. 
Meaning: The name "Gojra" means "cute" in Marathi, while its counterpart, Sajra Fort, means "smart". 
Location: Situated on the Naammam Malai hill, east of Vellore City in Tamil Nadu, these forts commanded the surrounding lower Vellore Fort. 
Outcome: The successful construction and bombardment from Gojra and Sajra Forts led to the surrender of the Vellore Fort, after which the Maratha Empire strengthened its fortifications and held it for three decades. 
</p>
    </body>
</html>

mahal.html
<html>
    <head>
        <title>Tipu and Hyder Mahal</title>
    </head>
    <body bgcolor="FFFFCC">
        <h2 align="center"><u>TIPU AND HYDER MAHAL</u></h2>
        <p align="justify" style="font-size: larger;">
            Tipu and Hyder Mahal are two historic palaces located within the Vellore Fort in Tamil Nadu, India. While the palaces bear the names of the famous 18th-century rulers of Mysore, Hyder Ali and his son Tipu Sultan, they were originally built by the Vijayanagara kings in the 16th century. The Mahals became associated with Hyder and Tipu after they were used to house Tipu's family during the British rule. 
        </p>
    </body>
</html>

sajra.html
<html>
    <head>
        <title>Sajra Fort</title>
    </head>
    <body bgcolor="FF9999">
        <h2 align="center" ><u>SAJRA FORT</u></h2>
        <p align="justify" style="font-size: larger;">
            Sajra Fort is a historical fort located in Vellore, Tamil Nadu, built by Chhatrapati Shivaji Maharaj's army in 1678 to help in the siege of Vellore Fort. Constructed on Naammam Malai hill, it served as a strategic position to bombard Vellore Fort, which was then under Bijapur control. The fort's name, along with its nearby counterpart, Gojra Fort, are Marathi words meaning "smart" and "cute" respectively.  
Key facts about Sajra Fort:
Builder: Chhatrapati Shivaji Maharaj's army. 
Purpose: To bombard the Vellore Fort during a siege in 1678. 
Location: On top of Naammam Malai hill, near Vellore Fort. 
History: The forts were built by Maratha Sardar Narhari Rudra and his army, enabling them to capture Vellore Fort after a 14-month siege. 
Status: Sajra Fort is a historic site, open to the public, but may pose safety concerns due to potential snakes and monkeys. 
Associated Structures: It is one of two forts, the other being Gojra Fort, that together dominated the surrounding area. 
        </p>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot (10).png>)
![alt text](<Screenshot (5).png>)
![alt text](<Screenshot (6).png>)
![alt text](<Screenshot (7).png>)
![alt text](<Screenshot (8).png>)
![alt text](<Screenshot (9).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
