
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>TCC - Tarayani Coaching Classes</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Poppins', sans-serif; }
    body { background: #f5f5f5; color: #333; }
    header { background: #004d99; color: white; padding: 20px; text-align: center; }
    header img { width: 100px; margin-bottom: 10px; }
    nav { background: #003366; display: flex; justify-content: center; padding: 10px; }
    nav a { color: white; text-decoration: none; margin: 0 15px; font-weight: 500; }
    nav a:hover { text-decoration: underline; }
    section { padding: 40px 20px; max-width: 1200px; margin: auto; }
    .hero { background: url('https://via.placeholder.com/1200x400') center/cover no-repeat; height: 300px; display: flex; align-items: center; justify-content: center; color: white; font-size: 2em; font-weight: bold; text-shadow: 2px 2px 4px #000; }
    .course, .contact, .form-section, .testimonial { background: white; padding: 20px; border-radius: 10px; margin-bottom: 20px; }
    footer { background: #222; color: #ccc; text-align: center; padding: 20px; }
    .gallery img { width: 100%; max-width: 300px; margin: 10px; border-radius: 8px; }
    .whatsapp-button {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #25D366;
      color: white;
      padding: 15px 20px;
      border-radius: 50px;
      text-decoration: none;
      font-weight: bold;
      box-shadow: 0 4px 6px rgba(0,0,0,0.3);
      z-index: 1000;
    }
    form label { display: block; margin: 10px 0 5px; }
    form input, form textarea { width: 100%; padding: 10px; margin-bottom: 15px; border-radius: 5px; border: 1px solid #ccc; }
    form button { background-color: #004d99; color: white; padding: 10px 20px; border: none; border-radius: 5px; cursor: pointer; }
    form button:hover { background-color: #003366; }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="TCC Logo">
    <h1>TCC - Tarayani Coaching Classes</h1>
    <p>Sainik School Entrance Exam Specialists</p>
  </header>

  <nav>
    <a href="#about">About Us</a>
    <a href="#courses">Courses</a>
    <a href="#gallery">Gallery</a>
    <a href="#testimonials">Testimonials</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="hero">
    Join TCC Today – Shape Your Future!
  </div>

  <section id="about">
    <h2>About Us</h2>
    <p>TCC – Tarayani Coaching Classes is dedicated to preparing students for Sainik School and other military school entrance exams. With experienced faculty and a focus on discipline and excellence, TCC is a trusted name in Gwalior.</p>
  </section>

  <section id="courses" class="course">
    <h2>Courses Offered</h2>
    <ul>
      <li>Sainik School Entrance Preparation</li>
      <li>RMS & RIMC Coaching</li>
      <li>Regular Tests & Doubt Sessions</li>
      <li>Weekly Assessments & Personal Mentorship</li>
    </ul>
  </section>

  <section id="gallery" class="gallery">
    <h2>Gallery</h2>
    <img src="https://via.placeholder.com/300x200?text=Classroom" alt="Classroom">
    <img src="https://via.placeholder.com/300x200?text=Students" alt="Students">
    <img src="https://via.placeholder.com/300x200?text=Events" alt="Events">
  </section>

  <section id="testimonials" class="testimonial">
    <h2>What Our Students Say</h2>
    <p><strong>Rohit S.:</strong> "TCC helped me clear my Sainik School entrance. Best coaching in town!"</p>
    <p><strong>Sneha M.:</strong> "Dedicated teachers and regular tests made all the difference."</p>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <p><strong>Address:</strong> TCC Building, Opposite HP Petrol Pump, Pinto Park, Gwalior</p>
    <p><strong>Phone:</strong> <a href="tel:9755147305">9755147305</a></p>
    <p><strong>Email:</strong> <a href="mailto:info@tcctarayani.com">info@tcctarayani.com</a></p>
    <iframe src="https://www.google.com/maps?q=Pinto+Park+HP+Petrol+Pump+Gwalior&output=embed" width="100%" height="300" style="border:0; margin-top:15px;" allowfullscreen="" loading="lazy"></iframe>
  </section>

  <section class="form-section">
    <h2>Inquiry Form</h2>
    <form action="#" method="post">
      <label for="name">Full Name:</label>
      <input type="text" id="name" name="name" required>

      <label for="phone">Phone Number:</label>
      <input type="tel" id="phone" name="phone" required>

      <label for="message">Your Message:</label>
      <textarea id="message" name="message" rows="4"></textarea>

      <button type="submit">Submit Inquiry</button>
    </form>
  </section>

  <a class="whatsapp-button" href="https://wa.me/919755147305" target="_blank">Chat on WhatsApp</a>

  <footer>
    <p>&copy; 2025 TCC - Tarayani Coaching Classes. All rights reserved.</p>
  </footer>
</body>
</html>
