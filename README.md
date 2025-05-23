# Ex04 Places Around Me
## Date: 09.05.2025

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
````
map.html

<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>srirangam</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>SATHYANARAYANAN M (24900472)</b></font>
</h3>
<center>
<!-- Image Map Generated by http://www.image-map.net/ -->
<img src="map.png" usemap="#image-map">
<map name="image-map">
    <area target="" alt="Amma Mandapam" title="Amma Mandapam" href="http://127.0.0.1:8000/static/lake.html" coords="290,671,481,740" shape="rect">
    <area target="" alt="Sri Ranganatha Swamy Temple, Srirangam" title="Sri Ranganatha Swamy Temple, Srirangam" href="http://127.0.0.1:8000/static/temple%201.html" coords="98,197,329,283" shape="rect">
    <area target="" alt="Thiruvanaikaval" title="Thiruvanaikaval" href="http://127.0.0.1:8000/static/temple2.html" coords="1035,552,813,490" shape="rect">
    <area target="" alt="Famous Residency" title="Famous Residency" href="http://127.0.0.1:8000/static/residency.html" coords="646,365,846,414" shape="rect">
</map>
</center>
</body>
</html>

lake.html
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="blue">
<h1 align="center">
<font color="red"><b>Srirangam</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Amma Mandapam</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    As Tiruchirappalli is surrounded by a lot of temples, churches, mosques and picnic spots on all directions,
    there are few more places in Trichy, which are radically distinctive from the above-named sites.
    They are Amma Mandapam and Kaveri Bridge (Cauvery bridge) which stuns tourists and local population with its never ceasing beauty.
    The Amma mandapam is a typical ghat (a stairway leading down to a landing in the Kaveri River) located 2 km away in the opposite direction of Srirangam Sri Ranganathar Swamy temple. 
    The Amma Mandapam ghat is the home of numerous ceremonies and rituals.The holy water of Kaveri River is collected in a golden pot and carried by the temple elephant Andal.
    While the elephant is accompanied by mangala isai from nadaswaram and thavil (music from a wind and percussive instrument) all the way to Srirangam temple,
    it is a unique ceremonial kind of a scene to be delighted.



</p>
</body>
</html>

temple 1.html
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>Srirangam</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Sri Ranganatha Swamy Temple, Srirangam</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    Sri Ranganathaswamy Temple, also known as Thiruvaranga Tirupati, is one of the most illustrious Vaishnav temples in the country, 
    dedicated to Ranganatha, a reclining form of Hindu deity, Bhagwan (God or Lord) Vishnu. Situated in an ethereal setting on the island of Srirangam that is bounded by the two rivers of Cauvery and Kollidam (a tributary of Cauvery),
    this living temple and sacred centre of pilgrimage is counted as the first and foremost among the 108 Divya Desams dedicated to Bhagwan Vishnu.
</p>
</body>
</html>

temple2.html
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="blue">
<h1 align="center">
<font color="red"><b>Srirangam</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Thiruvanaikaval</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    The Jambukeswarar Temple in Thiruvanaikaval is renowned in Tiruchirapalli district,
     in the south Indian state of Tamil Nadu. The temple is dedicated to Shiva. 
     The principal deity is Swayambhu (self-manifested).Jambukeswarar Temple, Thiruvanaikaval is a famous Shiva temple in Trichy,
     in the state of Tamil Nadu, India. The temple was built by Kocengannan (Kochenga Chola), one of the Early Cholas, around 1,800 years ago. 
     It is located in the Srirangam Island ,which also has another famous temple. Thiruvanaikal is one of the five major Shiva Temples of Tamil Nadu (Panchabhoota Sthalams) representing the five great elements.
     This temple represents the element of water. The sanctum sanctorum of Jambukeswarar temple has an underground water stream which keeps it always filled with water.
     
</p>
</body>
</html>

residency.html
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>Srirangam</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Famous Residency</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
    FAMOUS RESIDENCY is a great choice for travellers looking for a star hotel in Tiruchirappalli.
     This Hotel stands out as one of the highly recommended hotel in Tiruchirappalli.
     From all the Budget hotels in Tiruchirappalli, this property is very much popular among the tourists.
     You can find numerous hotels in Tiruchirappalli under different categories and this property is one the best hotel under its category.
     Whether it is a vacation with family or a business trip, everyone looks for safe hotels with the best facilities. In this hotel there is something for everyone to enjoy.
     Guests can expect a seamless check-in and check-out time to accommodate

</p>
</body>
</html>
`````


## OUTPUT
![image](https://github.com/user-attachments/assets/22310edc-00cd-41c7-ba59-6efe8dc005b0)

![image](https://github.com/user-attachments/assets/98458a84-48c2-40c9-a015-3ed9e72bafa5)

![image](https://github.com/user-attachments/assets/ee0eca97-3516-4fcf-9a0b-f56ee6a653e9)

![image](https://github.com/user-attachments/assets/c1c20d85-5024-4fb5-9ee7-d7dc13e0b393)


![image](https://github.com/user-attachments/assets/1a9bf101-b52c-46e5-8a8c-9904c7d5da31)




## RESULT
The program for implementing image maps using HTML is executed successfully.
