<!DOCTYPE html>
<html>
<head>
  <title>My Simple Website</title>
</head>
<body>

  <header>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="about">
      <h2>About Us</h2>
      <p>Welcome to our website! We are a company that specializes in providing top-notch services to our clients. Our team of experts is dedicated to delivering the best possible results for each project we take on. Contact us to learn more.</p>
    </section>

    <section id="services">
      <h2>Our Services</h2>
      <ul>
        <li>Service 1</li>
        <li>Service 2</li>
        <li>Service 3</li>
      </ul>
    </section>

    <section id="contact">
      <h2>Contact Us</h2>
      <form action="submit-form.php" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name">

        <label for="email">Email:</label>
        <input type="email" id="email" name="email">

        <label for="message">Message:</label>
        <textarea id="message" name="message"></textarea>

        <input type="submit" value="Submit">
      </form>
    </section>
  </main>

  <footer>
    <p>Copyright &copy; 2023 My Simple Website</p>
  </footer>

</body>
</html>
