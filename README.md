# Ex04 Places Around Me
## Date:22\04\2024

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
'''
map.html
<html>

    <head>
      <title>ayanavaram</title>
    </head>
    
    <body>
      <h1 align="center">
        <font color="black"><b>ayanavaram</b></font>
      </h1>
      <h2 align="center">
        <font color="black"><b>magesh.v(212222040092)</b></font>
      </h2>
    
    <center>
            <img src="mapp.png" usemap="#image-map">

            <map name="image-map">
                <area target="" alt="Marina Beach" title="Marina Beach" href="marinabeach.html" coords="1299,591,1344,811" shape="rect">
                <area target="" alt="Express avenue" title="Express avenue" href="expressavenue.html" coords="1181,611,48" shape="circle">
                <area target="" alt="D mart" title="D mart" href="dmart.html" coords="567,719,32" shape="circle">
                <area target="" alt="Sangam cinemas" title="Sangam cinemas" href="sangamcinemas.html" coords="1052,451,32" shape="circle">
                <area target="" alt="Chennai rail museum" title="Chennai rail museum" href="chennairailmuseum.html" coords="723,271,25" shape="circle">
            </map>
    </center>
    </body>
    
</html>
marinabeach.html
<html>
    <head>
        <title>Marina Beach</title>
        <h1 align="center">CHENNAI<h1>
         <h2 align="center" style="color:black;">Marina Beach<h2>   
<hr style="height:10px;background-color:white;width:100%">

    </head>
 <body bgcolor="green"> 
    <br>   
    <P align="center"> 
        Marina Beach, or simply the Marina, is a natural urban beach in Chennai, Tamil Nadu, India, along the Bay of Bengal. The beach runs from near Fort St. George in the north to Foreshore Estate in the south, 
		a distance of 6.0 km (3.7 mi),[1] making it the second longest urban beach in the world, after Cox's Bazar Beach.
		It is a prominent landmark in Chennai.The Marina is a primarily sandy beach, with an average width of 300 m (980 ft)[5] and the width at the widest stretch is 437 m (1,434 ft).
		Bathing and swimming at the Marina are legally prohibited because of the dangers, as the undercurrent is very turbulent. It is one of the most crowded beaches in the country and attracts about 30,000 visitors a day during weekdays[6] and 50,000 visitors a day during the weekends and on holidays.
		During summer months, about 15,000 to 20,000 people visit the beach daily.
</html>
expressavenue.html
<html>
    <head>
        <title>Express avenue</title>
        <h1 align="center">CHENNAI<h1>
         <h2 align="center" style="color:black;">Express avenue<h2>   
<hr style="height:10px;background-color:white;width:100%">

    </head>
 <body bgcolor="skyblue"> 
    <br>   
    <P align="center"> 
       Express Avenue is a shopping mall in Chennai promoted by Express Infrastructure, A division of Express Newspapers Pvt. Ltd.
	   which is bought by Ramnath Goenka from the monies of tha capitalists partner Raja Mohan Prasad and is held in trust by the current legal heirs for the family of Raja Mohan Prasad as per the trust deed given by Ramnath Goenka to Raja Mohan Prasad and is home to the largest gaming arcade in South India. 
	   Built at a cost of ₹7,500 million (US$94 million), the mall is spread over 1,750,000-square-foot (163,000 m2), including 900,000-square-foot (84,000 m2) of leasable (retail) area.
	   The mall has 8 anchor tenants and 150 vanilla tenants
</html>
dmart.html
<html>
    <head>
        <title>D_mart</title>
        <h1 align="center">CHENNAI<h1>
         <h2 align="center" style="color:black;">D_mart<h2>   
<hr style="height:10px;background-color:white;width:100%">

    </head>
 <body bgcolor="Salmon"> 
    <br>   
    <P align="center"> 
       Avenue Supermarts Limited, d/b/a DMart, is an Indian retail corporation that operates a chain of supermarkets in India.
	   It was founded by Radhakishan Damani in 2002 when its first store was opened in Powai, Mumbai.
	   As of 31 March 2024, it has 365 stores across 12 states and union territories in India.
	   The company has its headquarters in Mumbai.As of March 2023, DMart had a total of 12,108 permanent employees and 48,793 employees hired on contractual basis.
</html>
sangamcinemas.html
<html>
    <head>
        <title>Sangam Cinemas</title>
        <h1 align="center">CHENNAI<h1>
         <h2 align="center" style="color:black;">Sangam Cinemas<h2>   
<hr style="height:10px;background-color:white;width:100%">

    </head>
 <body bgcolor="Lavender"> 
    <br>   
    <P align="center"> 
       Sangam Multiplex - Kilpauk is a popular theatre located at 870, Poonamalle High Road, Near Hindustan Petrol Bunk, Kilpauk, Central, Chennai. Sangam Multiplex - Kilpauk has 3 screens.
	   Movies now showing at Sangam Multiplex - Kilpauk are Ghilli, Aavesham, Romeo and Dear.
	   Facilities available at Sangam Multiplex - Kilpauk are Parking Facility and Recliner Seats.
</html>
chennairailmuseum.html
<html>
    <head>
        <title>Chennai Rail Museum</title>
        <h1 align="center">CHENNAI<h1>
         <h2 align="center" style="color:black;">Chennai Rail Museum<h2>   
<hr style="height:10px;background-color:white;width:100%">

    </head>
 <body bgcolor="Cream"> 
    <br>   
    <P align="center"> 
      The Chennai Rail Museum is a railway museum in Chennai, Tamil Nadu, India.
	  The museum opened on 16 April 2002 in the Furnishing Division of the Integral Coach Factory (ICF) near Perambur. The 6.25-acre (2.53 ha) museum has technical and heritage exhibits, with a sizable collection of steam engines from the British Raj. 
	  It also has vintage coaches (such as Ooty trains), which were endemic on Indian railways. Most of the older models were manufactured by the North British Locomotive Company,
	  with some trains in the collection dating back more than a century.[2] Toy-train rides are available. There are 3 air-conditioned Indoor Galleries (ICF Gallery, Rail History Gallery, Art Gallery, 2 Other Non-airconditioned Galleries, a 90-seater air-conditioned Dolby Digital Movie Theatre (Railway and Railway Heritage Films), Natyarangam, Amphitheatre, a Number of Metal Sculptures made from scrap, 3D MURAL at the entrance, Cartoon Hero Characters better viewed from the Joyous Toy Train Ride, Rail Coach Restaurant, Eco Green Park, Lust Green vegetation, etc.,
	  The museum is managed and maintained by the ICF.
</html>
'''

## OUTPUT
![1](https://github.com/magesh534/NearMe/assets/135577936/a27387d4-65e2-4a13-ab54-67a3d9d5557e)
![2](https://github.com/magesh534/NearMe/assets/135577936/ea6556c4-8135-429d-a9a5-661f844e0bd7)
![3](https://github.com/magesh534/NearMe/assets/135577936/a8e472c3-cd1d-4c64-b560-171da85687bf)
![4](https://github.com/magesh534/NearMe/assets/135577936/b8180271-a792-47de-bb65-117ca0906c6e)
![5](https://github.com/magesh534/NearMe/assets/135577936/e1dd00fd-1925-407c-89db-3b75289c5aba)

## RESULT
The program for implementing image maps using HTML is executed successfully.
