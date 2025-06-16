<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>VRS Tax Filing Services</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f4; /* Light yellow background */
      color: violet; /* Dark content text */
    }
    header {
      background: #002b5c;
      color: green;
      padding: 30px 20px;
      text-align: center; /* Re-centered header */
    }
    header h1 {
      margin: 0;
      font-size: 38px;
    }
    nav {
      background: #004080;
      padding: 12px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      background: white;
      padding: 25px;
      max-width: 1000px;
      margin: 20px auto;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }
    footer {
      background: #111;
      color: #ccc;
      text-align: center;
      padding: 15px;
      margin-top: 30px;
    }
    .button {
      background: #007BFF;
      color: white;
      padding: 12px 20px;
      border: none;
      cursor: pointer;
      text-decoration: none;
      border-radius: 5px;
      display: inline-block;
      font-size: 16px;
      transition: background 0.3s ease;
    }
    .button:hover {
      background: #0056b3;
    }
    input, textarea, select {
      width: 100%;
      padding: 12px;
      margin-top: 10px;
      margin-bottom: 20px;
      border: 1px solid #ccc;
      border-radius: 5px;
      box-sizing: border-box;
    }
    form {
      max-width: 600px;
      margin: auto;
    }
    ul {
      padding-left: 20px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to VRS Tax Filing Services</h1>			
    <p>Professional GST, TDS, TCS, and Income Tax Return Filing</p>
 <div class="highlight-banner">
   <marquee behavior="scroll" direction="left"scrollamount="6">
    🔔 <strong>GST Return : Free of Cost up to 15 records, More than 15 records Rs.450/month</strong> 🔔
  </marquee>
</div>
  </header>
  <nav>
    <a href="#services">Services</a>
    <a href="#about">About</a>
    <a href="#pricing">Pricing</a>
    <a href="#contact">Contact</a>
    <a href="#upload">Upload Docs</a>
  </nav>

  <section id="services">
    <h2>Our Services</h2>
    <ul>
      <li>GST Registration & Return Filing</li>
      <li>TDS/TCS Compliance & Return</li>
      <li>Income Tax Return Filing (Salaried, Business, Freelancers)</li>
      <li>Tax Notice Handling & Consultancy</li>
    </ul>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>I am a professional tax accountant with over 17 years of experience in private limited companies. I specialize in GST, TDS, TCS, and Income Tax services. Now offering direct services to individuals and businesses for better financial outcomes.</p>
  </section>

  <section id="pricing">
    <h2>Pricing Plans</h2>
    <ul>
      <li><strong>GST Returns:</strong> Up to 15 records completely Free of Cost, more than 15 records Rs. 450/month</li>
      <li><strong>Notice Handling:</strong> Rs. 750/- per case</li>
      <li><strong>TDS/TCS Return:</strong> Rs. 450/-per Qtr</li>
      <li><strong>Salaried ITR:</strong> Rs. 350/-</li>
      <li><strong>Business ITR:</strong> Rs. 1000/-</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: <a href="mailto:raghuvnpuram@gmail.com">raghuvnpuram@gmail.com</a></p>
    <p>Phone / WhatsApp: <a href="tel:+918825996221">+91-8825996221</a></p>
    <a href="mailto:raghuvnpuram@gmail.com" class="button">Send Email</a>
  </section>

  <section id="upload">
    <h2>Upload Documents</h2>
    <form action="#" method="post" enctype="multipart/form-data">
      <label for="name">Full Name:</label>
      <input type="text" id="name" name="name" required>

      <label for="email">Email Address:</label>
      <input type="email" id="email" name="email" required>

      <label for="phone">Phone Number:</label>
      <input type="text" id="phone" name="phone" required>

      <label for="doc">Upload Your Documents (PDF/JPG):</label>
      <input type="file" id="doc" name="document" accept=".pdf,.jpg,.jpeg,.png" required>

      <button type="submit" class="button">Submit</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 VRS Tax Filing Services. All Rights Reserved.</p>
  </footer>

</body>
</html>
