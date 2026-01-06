<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sacred Hooves â€“ Cow Protection</title>


<style>
body{
Â  margin:0;
Â  font-family:Arial, sans-serif;
Â  background:#f4fff0;
Â  line-height:1.6;
}
header{
Â  background:#2e7d32;
Â  color:white;
Â  text-align:center;
Â  padding:25px 10px;
}
header h1{
Â  margin:0;
Â  font-size:2.2rem;
}
nav{
Â  background:#1b5e20;
Â  display:flex;
Â  flex-wrap:wrap;
Â  justify-content:center;
Â  padding:10px;
Â  position:sticky;
Â  top:0;
Â  z-index:1000;
}
nav a{
Â  color:white;
Â  margin:6px 10px;
Â  text-decoration:none;
Â  font-weight:bold;
Â  font-size:0.95rem;
}
nav a:hover{
Â  text-decoration:underline;
}
section{
Â  padding:40px 15px;
Â  max-width:1100px;
Â  margin:auto;
}
h2, h3{
Â  color:#2e7d32;
}
img{
Â  max-width:100%;
Â  height:auto;
Â  border-radius:10px;
Â  margin-top:15px;
}
.gallery{
Â  display:grid;
Â  grid-template-columns:repeat(auto-fit, minmax(220px,1fr));
Â  gap:20px;
Â  margin-top:20px;
}
button{
Â  background:#2e7d32;
Â  color:white;
Â  padding:12px 22px;
Â  border:none;
Â  border-radius:5px;
Â  cursor:pointer;
Â  font-size:1rem;
}
button:hover{
Â  background:#1b5e20;
}
input, textarea{
Â  width:100%;
Â  padding:12px;
Â  margin:8px 0;
Â  border:1px solid #ccc;
Â  border-radius:5px;
Â  font-size:1rem;
}
footer{
Â  background:#2e7d32;
Â  color:white;
Â  text-align:center;
Â  padding:12px;
Â  font-size:0.9rem;
}


/* WhatsApp Floating Button */
.whatsapp-btn{
Â  position:fixed;
Â  bottom:20px;
Â  right:20px;
Â  background:#25D366;
Â  color:white;
Â  border-radius:50px;
Â  padding:12px 18px;
Â  display:flex;
Â  align-items:center;
Â  text-decoration:none;
Â  font-weight:bold;
Â  box-shadow:0 4px 8px rgba(0,0,0,0.3);
Â  z-index:2000;
}
.whatsapp-btn img{
Â  width:28px;
Â  margin-right:10px;
}
.whatsapp-btn:hover{
Â  background:#1ebe5d;
}


@media (max-width:600px){
Â  header h1{
Â  Â  font-size:1.7rem;
Â  }
Â  nav a{
Â  Â  font-size:0.85rem;
Â  Â  margin:5px;
Â  }
}
</style>
</head>


<body>


<header>
Â  <h1>SACRED HOOVES</h1>
Â  <p>Protect Cows â€¢ Protect Nature â€¢ Protect Life</p>
</header>


<nav>
Â  <a href="#home">Home</a>
Â  <a href="#about">About</a>
Â  <a href="#importance">Importance</a>
Â  <a href="#products">Cow Products</a>
Â  <a href="#rescue">Rescue</a>
Â  <a href="#volunteer">Volunteer</a>
Â  <a href="#donate">Donate</a>
Â  <a href="#contact">Contact</a>
</nav>


<section id="home">
Â  <h2>Our Mission</h2>
Â  <p>
Â  Â  Sacred Hooves is dedicated to the rescue, protection, and welfare of cows.
Â  Â  We provide shelter, medical care, and promote awareness about cow protection.
Â  </p>
Â  <img src="https://images.unsplash.com/photo-1590502593747-42a996133562" alt="Indian Cow">
</section>


<section id="about">
Â  <h2>About Sacred Hooves</h2>
Â  <p>
Â  Â  Sacred Hooves is a cow protection initiative based in Bangalore.
Â  Â  We work to rescue abandoned and injured cows and promote sustainable living.
Â  </p>
Â  <div class="gallery">
Â  Â  <img src="https://images.unsplash.com/photo-1560807707-8cc77767d783">
Â  Â  <img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee">
Â  Â  <img src="https://images.unsplash.com/photo-1609252509102-a7f28f5c1b35">
Â  </div>
</section>


<section id="importance">
Â  <h2>Importance of Cow</h2>
Â  <p>
Â  Â  The cow plays a vital role in Indian culture, agriculture, and the environment.
Â  Â  Cows support sustainable farming, rural economy, and ecological balance.
Â  </p>
</section>


<section id="products">
Â  <h2>Importance of Cow Products</h2>
Â  <h3>Milk & Ghee</h3>
Â  <p>Nutritious, immunity-boosting, and essential for food and health.</p>
Â  <h3>Cow Dung</h3>
Â  <p>Used as organic manure, biogas, and eco-friendly products.</p>
Â  <h3>Cow Urine (Gomutra)</h3>
Â  <p>Used in traditional medicine and organic farming.</p>
Â  <h3>Marketing & Distribution</h3>
Â  <p>
Â  Â  Sacred Hooves markets cow products ethically and delivers them to
Â  Â  orphanages, old-age homes, poor families, and farmers.
Â  </p>
</section>


<section id="rescue">
Â  <h2>Emergency Cow Rescue</h2>
Â  <p>Share your live GPS location for immediate rescue.</p>
Â  <img src="https://images.unsplash.com/photo-1546443046-ed1ce6ffd1ab">
Â  <br><br>
Â  <button onclick="getLocation()">Share Emergency Location</button>
Â  <p id="location"></p>
</section>


<section id="volunteer">
Â  <h2>Volunteer With Us</h2>
Â  <img src="https://images.unsplash.com/photo-1603187083444-94c9f3dbd0c5">
Â  <form action="mailto:manushreeg27@gmail.com" method="post" enctype="text/plain">
Â  Â  <input type="text" name="Name" placeholder="Your Name" required>
Â  Â  <input type="text" name="Phone" placeholder="Phone Number" required>
Â  Â  <textarea name="Address" placeholder="Address"></textarea>
Â  Â  <textarea name="Service" placeholder="How can you help?"></textarea>
Â  Â  <button type="submit">Apply as Volunteer</button>
Â  </form>
</section>


<section id="donate">
Â  <h2>Donate to Sacred Hooves</h2>
Â  <p>Your donation helps rescue, feed, and shelter cows.</p>
Â  <img src="https://images.unsplash.com/photo-1588072432836-e10032774350">
Â  <p><b>UPI ID:</b> sacredhooves@upi</p>
Â  <p>Google Pay â€¢ PhonePe â€¢ Paytm â€¢ Bank Transfer</p>
</section>


<section id="contact">
Â  <h2>Contact Us</h2>
Â  <p><b>Address:</b> Pattanagere, R R Nagar, Bangalore</p>
Â  <p><b>Phone:</b> 7899574243</p>
Â  <p><b>Email:</b> manushreeg27@gmail.com</p>
</section>


<footer>
Â  Â© 2026 Sacred Hooves | Cow Protection Initiative
</footer>


<!-- WhatsApp Button -->
<a class="whatsapp-btn"
Â  Â href="https://wa.me/917899574243?text=Hello%20Sacred%20Hooves,%20I%20need%20help%20regarding%20cow%20rescue."
Â  Â target="_blank">
Â  <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg">
Â  WhatsApp Us
</a>


<script>
function getLocation(){
Â  if(navigator.geolocation){
Â  Â  navigator.geolocation.getCurrentPosition(showPosition);
Â  }else{
Â  Â  alert("GPS not supported");
Â  }
}
function showPosition(position){
Â  const lat = position.coords.latitude;
Â  const lon = position.coords.longitude;
Â  document.getElementById("location").innerHTML =
Â  Â  "Latitude: " + lat + "<br>Longitude: " + lon +
Â  Â  `<br><a href="https://www.google.com/maps?q=${lat},${lon}" target="_blank">
Â  Â  Open in Google Maps</a>`;
}
</script>


</body>
</html>
