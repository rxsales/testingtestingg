<!DOCTYPE html>
<html>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
<style>
body,h1,h5 {font-family: "Raleway", sans-serif}
body, html {height: 100%}
.bgimg {
  background-image: url('https://upload.wikimedia.org/wikipedia/commons/thumb/e/ea/US_Navy_100813-N-3589B-096_Sailors_participate_in_a_community_plant_schrubs_with_local_children_during_a_community_service_project_at_the_Village_of_Hope_orphanage_in_Vietnam.jpg/1280px-thumbnail.jpg');
  min-height: 100%;
  background-position: center;
  background-size: cover;
}
#Titlee {
  background-color: Black;
}
</style>
<body>

<div class="bgimg w3-display-container w3-text-white">
<div class="w3-display-middle w3-jumbo">
  <p id= "Titlee"> WISE MARK </p>
</div>
<div class="w3-display-topleft w3-container w3-xlarge">
  <p><button onclick="document.getElementById('issues').style.display='block'" class="w3-button w3-black">Issues</button></p>
  <p><button onclick="document.getElementById('Post').style.display='block'" class="w3-button w3-black">Post</button></p>
  <p><button onclick="document.getElementById('About').style.display='block'" class="w3-button w3-black">About</button></p>
</div>
<div class="w3-display-bottomleft w3-container">
  <p class="w3-xlarge">"Helping one person might not change the whole world, but it could change the world for one person."</p>
  <p class="w3-large">Los Angeles, California</p>
  <p>Created by Karen Rosales, Stephanie Ibrahim, Elle Weingarten, Ani Muckelroy </p>
</div>
</div>


<!-- Issues Modal -->
<div id="issues" class="w3-modal">
  <div class="w3-modal-content w3-animate-zoom">
    <div class="w3-container w3-black w3-display-container">
      <span onclick="document.getElementById('issues').style.display='none'" class="w3-button w3-display-topright w3-large">x</span>
      <h1>Animals</h1>
    </div>
    <div class="w3-container">
  <h3>  <a href= "http://www.laanimalservices.com/volunteer" >LA Animal Services </a> </h3>
  <img src = "http://www.laanimalservices.com/wp-content/uploads/2011/06/Dog4.png">
      <h5>With this organization, you can do many different things. You can walk, bathe, and play with dogs. You can also update the
        organization’s web page or photograph the animals. Lastly, you can help get people to adopt the animals.<br>Contact info: 888-452-7381</h5>

      <h3> <a href ="https://www.adoptandshop.org/"> Adopt and Shop </a></h3>
      <img src = <img src = "http://www.laanimalservices.com/wp-content/uploads/2011/06/Dog4.png">
      <h5>  This organization in Culver City and Lakewood has opportunities for ages 13 and up. You can be a pet care provider, retail and adoption counselor, daycare assistant, etc. You must commit to a minimum of 3 months of service and contribute at least 8 hours of service per month.
<br>Contact Info: Culver City: 310-933-6863
Lakewood: 562-531-2871
</h5>
    </div>
    <div class="w3-container w3-black">
      <h1>Homelessness </h1>
    </div>
    <div class="w3-container">
      <h5>Grilled Fish and Potatoes <b>$8.50</b></h5>
      <h5>Italian Pizza <b>$5.50</b></h5>
      <h5>Veggie Pasta <b>$4.00</b></h5>
      <h5>Chicken and Potatoes <b>$6.50</b></h5>
      <h5>Deluxe Burger <b>$5.00</b></h5>
    </div>
    <div class="w3-container w3-black">
      <h1>Women and Children</h1>
    </div>
    <div class="w3-container">
      <h5>Fruit Salad <b>$2.50</b></h5>
      <h5>Ice cream <b>$2.00</b></h5>
      <h5>Chocolate Cake <b>$4.00</b></h5>
      <h5>Cheese <b>$5.50</b></h5>
    </div>
    <div class="w3-container w3-black">
      <h1>Hospitals</h1>
    </div>
    <div class="w3-container">
      <h5>Fruit Salad <b>$2.50</b></h5>
      <h5>Ice cream <b>$2.00</b></h5>
      <h5>Chocolate Cake <b>$4.00</b></h5>
      <h5>Cheese <b>$5.50</b></h5>
    </div>
    <div class="w3-container w3-black">
      <h1>Enviroment</h1>
    </div>
    <div class="w3-container">
      <h5>Fruit Salad <b>$2.50</b></h5>
      <h5>Ice cream <b>$2.00</b></h5>
      <h5>Chocolate Cake <b>$4.00</b></h5>
      <h5>Cheese <b>$5.50</b></h5>
    </div>
    <div class="w3-container w3-black">
      <h1>Education</h1>
    </div>
    <div class="w3-container">
      <h5>Fruit Salad <b>$2.50</b></h5>
      <h5>Ice cream <b>$2.00</b></h5>
      <h5>Chocolate Cake <b>$4.00</b></h5>
      <h5>Cheese <b>$5.50</b></h5>
    </div>
  </div>
</div>

<!-- Contact Modal -->
<div id="contact" class="w3-modal">
  <div class="w3-modal-content w3-animate-zoom">
    <div class="w3-container w3-black">
      <span onclick="document.getElementById('contact').style.display='none'" class="w3-button w3-display-topright w3-large">x</span>
      <h1>Contact</h1>
    </div>
    <div class="w3-container">
      <p>Reserve a table, ask for today's special or just send us a message:</p>
      <form action="/action_page.php" target="_blank">
        <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Name" required name="Name"></p>
        <p><input class="w3-input w3-padding-16 w3-border" type="number" placeholder="How many people" required name="People"></p>
        <p><input class="w3-input w3-padding-16 w3-border" type="datetime-local" placeholder="Date and time" required name="date" value="2017-11-16T20:00"></p>
        <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Message \ Special requirements" required name="Message"></p>
        <p><button class="w3-button" type="submit">SEND MESSAGE</button></p>
      </form>
    </div>
  </div>
</div>

</body>
</html>
