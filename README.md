# User Centre Project: Restaurant Website

The projects aim is create a website for Thunder Road cafe a restaurant in Dublin.

Original wireframe at   /Documentation/restaurntproject-wireframe.pdf


The key goals of the new website are:

 Improve Mobile Web Experience
  * Increase Bookings
  * Encourage Customers to Join VIP Club (mail list)

Website statistics show that over 70% of the Web access for the existing site  is by mobile devices. Based on this the website  design us primary a “One Page” with a separate page for the restaurant menu.  This creates a seamless user experiences and minimises load/wait times.


## Use Cases

We have identified 3 major use cases


* Customer With Booking Intent

  This Use Case represents a customer who knows the restaurant and accesses the website to book a table.  The goal heres is to reduce “friction’ in booking a table.

* ‘Search” Customer

  This represents a customer who is looking for a restaurant to dine in “same day”, they will typically come from Google or Google Maps. 
  The Goals here are to clearly communicate the restaurant brand message and identity and encourage the customer to book.
        
* Tourist /Trip Advisor

  This Use Case represents tourists planning a trip to Dublin, perhaps weeks in advance. They will typically find the restaurant via Trip Advisor. Our primary goal is to encourage/allow the customer book a table, while our secondary goal is to motivate them to join the restaurant mail-list (VIP Club) from where they will receive promotions.

 


# UX


The sections of the website are 

## Header Section

This section provides the logo, Restaurant “Elevator Pitch’”, 
“Hero Image” and links to the Open Table booking widget. (third party software)

This supports all Use Cases by clearly articulating the restaurant’s  USP and facilitating quick and easy bookings. 

The food menu is easily accessible and opens a new page.


## About Us 

The get section communicates the restaurants focus in key images and the idea of 
Eat-Drink-Party.


## Featured

This section highlights awards won and customer feedbacl.


## Get In Touch

This section allows customers contact the restaurant and find it’s exact location. It also allows customer signup to the restaurants VIP Club.


This supports Use Cases for tourists by enabling queries and also allows people find the restaurant using Google maps. It also allows customer register for special offer, allowing the restaurant follow up with the customer to encourage them to visit.


## Inside ThunderRoad

This section allows highlight fund and friendly staff and presents promotional video which allows the user find out more about the restaurant.


## Lets Get Social

This sections highlights the restaurant’s social media presence and allows the customer to connect.


Navigtaion Approach
The website used a standard menu system with a callapses when as the devide size becomes smaller.
I considered making the meny 'stick' to the top using but decided against this to maximise informaton we could prpvides
on samll devies (70% if usage), the sequence of the sections was designed to provide key requirements (booking and vip signups) in as simple and intuitives manner as possible,




# Technology

The key technology elements we will use and link to are:

. Html
. Bootstrap 4
. Opentable for booking (third party sofwar Javascript code provided )
. Vimeo for Video Hosting


# Deployment

  The code is deployed to Git Hub and available at Githibs Pages.
  
   The links below give direct access.
   
   Repositary: https://github.com/pcumiskeyboomerang/CIRESTAURANTPROJECT
   
   Git Pages UrL: https://pcumiskeyboomerang.github.io/CIRESTAURANTPROJECT/
   
   
   
   
# Testing


## Overview 

The website design is primarily based on one page with a separate page for the restaurant menu.

The key elements of testing were Navigation, Use of the booking form, Input Field Validation and responsiveness. Each section is discussed bellow, a detailrf Testing Checklist is also provided in the test documentation folder.


## Navigation

All menu options were tested to ensure the user is brought the to the correct section.
The “Email’ links open up the default email manager.
The Social Links (Youtube, Facebook and Instagram) all open the correct social page.

## Bookings

 “Opentable” a well established table booking system is used by the restaurant. I obtained a standard script to allow the ‘booking widget’ to be embedded in the system,
 
 When the button is clicked an “open table” pages is opened the customer may book a table.

This process was check to ensure a booking was fully completed,

Note: As ‘open table” new page is opened and do not have access to open table code , in this version the customer doers not return to the restaurant website after completing their booking.
 it is expected we will enhance the system to return at a later in a later version.


## Input Form

The input form capture email and name. 
Both fields are required and the email must be have a valid format.
The system was tested for blank field submissions and invalid email formats.
The submit button does not currently operate as the script required is beyond the scope of the project. 



## Responsiveness

The site Was check on across Firefox, Safari and Google Chrome.

Google Developer tools was used to test responsiveness across all devices.

The website was also testing on iMac, Acer chromeBOOK Ipad , Samsung J5, Amazon Fire Table





# Credits

Image and Videos  by Thunderroad cafe.
Booking form provided by Opentable



# Acknowledgments
Assistance provided by Thunderroad is providing swebsite requirements
