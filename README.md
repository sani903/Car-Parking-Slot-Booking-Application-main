# Parking Slot Booking Web Application
A parking slot booking app to fulfil your parking requirements! Now you'll never have to worry about where to park your vehicle anymore!
This web application will help you find a parking spot at your desired location just with a few clicks!

<h3 align="left">Languages and Frameworks used:</h3>  
<p align="left"> <a href="https://getbootstrap.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://spring.io/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" alt="spring" width="40" height="40"/> </a> </p>


Prior to development, it was designed and wireframed in Figma.

Here is the flow of the website along with what the user sees at each step (from the Figma design):
> A new customer must first create an account in order to use the application. They are taken to the Registration Page to create their unique user id and password.
---
**Registration Page:**
<br><br>
<a href="https://lh3.googleusercontent.com/zLzk9XNlTRXBgj0w2vpsPaaW8Q53Ym2u8-AZd3AdNk8cAgj7cn_Ftz3d97gyO9b1muWHxa7Sx9GtQn-jmKfxxPnu6Q1gE7A_gh6NQptm5ccXO9pLu2QwmnDE8E0tN2xorcbc2WgS=w2400?source=screenshot.guru"> <img src="https://lh3.googleusercontent.com/zLzk9XNlTRXBgj0w2vpsPaaW8Q53Ym2u8-AZd3AdNk8cAgj7cn_Ftz3d97gyO9b1muWHxa7Sx9GtQn-jmKfxxPnu6Q1gE7A_gh6NQptm5ccXO9pLu2QwmnDE8E0tN2xorcbc2WgS=w600-h315-p-k" /> 
</a>
> After a new registration, the customer is redirected to the Login Page.
---
**Login Page:**<br><br>
<a href="https://lh3.googleusercontent.com/OLX3mux9P3M60gjcrU5i1dlb1XYbe13VXqkeOwAFdC2dymN8JzNNiYjqrs7hKi7d7YbWl9sOivlFbZaCHSUA77jbtWN7VS3qQ8LycUTKlQ_I7RWwAnQFUnb6xWOiwvOiiYUmqB0L=w2400?source=screenshot.guru"> <img src="https://lh3.googleusercontent.com/OLX3mux9P3M60gjcrU5i1dlb1XYbe13VXqkeOwAFdC2dymN8JzNNiYjqrs7hKi7d7YbWl9sOivlFbZaCHSUA77jbtWN7VS3qQ8LycUTKlQ_I7RWwAnQFUnb6xWOiwvOiiYUmqB0L=w600-h315-p-k" /> 
</a>
> The Login Page uses RBAC to grant access to either Customer or Admin, and does not allow unauthorised users.
> Once the customer has logged in, they are taken to the Customer Dashboard.
---
**Customer Dashboard:**<br><br>
<a href="https://lh3.googleusercontent.com/uGREqnyygRIl19BwCDWrtuRUO10znu_88WAd7tu-EIqREE8vCv4KZSO7OA7zDYCyYYb6gz4SIBI1ugyLcek4MGSs8Xa3lGXZDHmdfrXGCjU5RANmYKqdavrT2f9LAH5aG9SYtMIK=w2400?source=screenshot.guru"> <img src="https://lh3.googleusercontent.com/uGREqnyygRIl19BwCDWrtuRUO10znu_88WAd7tu-EIqREE8vCv4KZSO7OA7zDYCyYYb6gz4SIBI1ugyLcek4MGSs8Xa3lGXZDHmdfrXGCjU5RANmYKqdavrT2f9LAH5aG9SYtMIK=w600-h315-p-k" /> </a>
> - Here, the customer can enter where they would like to book a parking spot, the date, and the time. Besides this, they may opt for one or more vehicle maintenance services like window cleaning, changing the oil, etc.
> - Upon clicking "Confirm Booking", the customer will be taken to a payment page, where they must pay using their e-wallet, and then complete their booking procedure.
---
**Admin Dashboard:**<br><br>
<a href="https://lh3.googleusercontent.com/BXJS_HkoemkVF9_BDdBls2aCy1nkEB1NoZXuEa5g6whwey2P23_FOjWCV5oK3WTSclSoBfrgeMO1NBvynMuif87vCM9I6o6iyWUTGulKAPYNlrYgHqXbUEDnS256y1uE15yImKRf=w2400?source=screenshot.guru"> <img src="https://lh3.googleusercontent.com/BXJS_HkoemkVF9_BDdBls2aCy1nkEB1NoZXuEa5g6whwey2P23_FOjWCV5oK3WTSclSoBfrgeMO1NBvynMuif87vCM9I6o6iyWUTGulKAPYNlrYgHqXbUEDnS256y1uE15yImKRf=w600-h315-p-k" /> </a>
> If the user logging in is the Admin, they will be taken to the Admin Dashboard. Here the Admin can add/remove various services such as locations, working hours, workers at a location, and the additional services provided.
---
**Other resources used:**
- *Google Fonts:* https://fonts.google.com/
- *Color Palette:* https://coolors.co/
- *Figma Design (personal design):* https://rb.gy/8z1zu3
