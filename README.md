# hostel
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Student Housing - Warsaw Wola</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #fafafa;
      color: #333;
    }
    header {
      background: #4CAF50;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    nav {
      text-align: center;
      margin: 1rem 0;
    }
    nav a {
      margin: 0 1rem;
      text-decoration: none;
      color: #4CAF50;
      font-weight: bold;
    }
    .container {
      width: 90%;
      max-width: 1000px;
      margin: auto;
    }
    .room-card {
      background: white;
      border-radius: 10px;
      padding: 1rem;
      margin: 1rem 0;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      display: flex;
      gap: 1rem;
    }
    .room-card img {
      width: 200px;
      height: 150px;
      object-fit: cover;
      border-radius: 10px;
    }
    .room-info h3 {
      margin-top: 0;
    }
    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Student Housing in Wola, Warsaw</h1>
    <p>Affordable, comfortable rooms for students</p>
  </header>

  <nav>
    <a href="#rooms">Rooms</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="container" id="rooms">
    <h2>Available Rooms</h2>

    <div class="room-card">
      <img src="https://via.placeholder.com/200x150" alt="Room photo">
      <div class="room-info">
        <h3>Single Room</h3>
        <p>Cozy single room with desk, Wi-Fi, and shared kitchen.</p>
        <p><strong>Price:</strong> 1500 PLN / month</p>
      </div>
    </div>

    <div class="room-card">
      <img src="https://via.placeholder.com/200x150" alt="Room photo">
      <div class="room-info">
        <h3>Shared Room</h3>
        <p>Spacious shared room for two students, all utilities included.</p>
        <p><strong>Price:</strong> 1000 PLN / month per person</p>
      </div>
    </div>
  </div>

  <div class="container" id="about">
    <h2>About Us</h2>
    <p>We provide student-friendly housing in the heart of Wola, Warsaw. Walking distance to metro, shops, and universities. Fully furnished rooms with fast internet and study-friendly environment.</p>
  </div>

  <div class="container" id="contact">
    <h2>Contact</h2>
    <p>Email: housingwola@example.com</p>
    <p>Phone: +48 600 123 456</p>
  </div>

  <footer>
    <p>&copy; 2025 Student Housing Wola. All rights reserved.</p>
  </footer>
</body>
</html>
