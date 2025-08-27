# web_site-v1
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Hotel Bliss</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #2c3e50;
      color: white;
      padding: 1rem;
      text-align: center;
    }

    nav {
      background-color: #34495e;
      display: flex;
      justify-content: center;
      gap: 2rem;
      padding: 0.5rem;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    .grid {
      display: grid;
      grid-template-columns: 1fr 2fr;
      gap: 1rem;
      padding: 1rem;
    }

    .pic {
      width: 100%;
      height: 300px;
      object-fit: cover;
    }

    section {
      padding: 1rem;
    }

    footer {
      background-color: #2c3e50;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }

    marquee {
      height: 200px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Hotel Bliss</h1>
    <p>Your comfort, our priority</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#services">Services</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact Us</a>
  </nav>

  <div class="grid">
    <div>
      <h3>📰 Notifications</h3>
      <marquee direction="up" scrollamount="3">
        <p>Summer discount: 20% off on deluxe rooms</p><br>
        <p>Free breakfast included for all bookings in August</p><br>
        <p>New rooftop restaurant now open!</p><br>
      </marquee>
    </div>
    <div>
      <img src="hotel.jpg" alt="Hotel Image" class="pic">
    </div>
  </div>

  <section id="services">
    <h2 style="text-align:center;">Our Services</h2>
    <hr>
    <ul>
      <li>Room Booking</li>
      <li>Banquet Hall Reservations</li>
      <li>Spa & Wellness</li>
      <li>24/7 Room Service</li>
      <li>Airport Pickup & Drop</li>
    </ul>
  </section>

  <section id="gallery">
    <h2 style="text-align:center;">Gallery</h2>
    <hr>
    <p style="text-align:center;">[Images of rooms, lobby, restaurant, etc. can be added here]</p>
  </section>

  <section id="contact">
    <h2 style="text-align:center;">Contact Us</h2>
    <hr>
    <p>Email: info@hotelbliss.com</p>
    <p>Phone: +91-9876543210</p>
    <p>Address: 123 Paradise Lane, Jalandhar, Punjab</p>
  </section>

  <footer>
    <p>&copy; 2025 Hotel Bliss. All rights reserved.</p>
  </footer>

</body>
</html>
