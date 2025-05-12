# Biswas-Paribahan
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>SwiftRide Bus Services</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>
  <header>
    <h1>SwiftRide</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#search">Book Tickets</a>
      <a href="#about">About Us</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="home">
    <h2>Welcome to SwiftRide</h2>
    <p>Your trusted travel partner across India.</p>
  </section>

  <section id="search">
    <h2>Book Your Bus</h2>
    <form>
      <label>From: <input type="text" placeholder="Source City" required></label><br>
      <label>To: <input type="text" placeholder="Destination City" required></label><br>
      <label>Date: <input type="date" required></label><br>
      <button type="submit">Search Buses</button>
    </form>
  </section>
  body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  line-height: 1.6;
  background-color: #f4f4f4;
}

header {
  background: #007bff;
  color: white;
  padding: 1rem;
  text-align: center;
}

nav a {
  color: white;
  margin: 0 10px;
  text-decoration: none;
  font-weight: bold;
}

section {
  padding: 20px;
  background: white;
  margin: 10px;
  border-radius: 8px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

form input, form button {
  margin: 5px 0;
  padding: 8px;
  width: 200px;
}

button {
  background: #007bff;
  color: white;
  border: none;
  cursor: pointer;
}

footer {
  text-align: center;
  background: #333;
  color: white;
  padding: 10px;
}

  <section id="about">
    <h2>About Us</h2>
    <p>SwiftRide offers safe, punctual and affordable travel options with a fleet of over 200 buses.</p>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: support@swiftride.com</p>
    <p>Phone: +91-9876543210</p>
  </section>

  <footer>
    <p>© 2025 SwiftRide. All rights reserved.</p>
  </footer>
</body>
</html>
