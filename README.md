<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>NSS NSUT</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      line-height: 1.6;
      background-color: #f0eeee;
    }

    header {
      background-color: #ff0000;
      color: #f8f8f8;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }

    .logo {
      font-size: 1.8rem;
      font-weight: 600;
    }

    nav a {
      color: #ffffff;
      text-decoration: none;
      margin-left: 20px;
      font-weight: 500;
    }

    .hero {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      padding: 60px 20px;
      background: url('https://nssnsut.vercel.app/assets/hero-bg.webp') no-repeat center/cover;
      color: rgb(136, 132, 132);
      text-align: center;
    }

    .hero h1 {
      font-size: 2.5rem;
      margin-bottom: 20px;
    }

    .hero p {
      font-size: 1.1rem;
      max-width: 600px;
    }

    .section {
      padding: 60px 20px;
      text-align: center;
    }

    .section h2 {
      font-size: 2rem;
      margin-bottom: 20px;
    }

    .section p {
      max-width: 800px;
      margin: 0 auto 40px;
    }

    .card-container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 0 20px;
    }

    .card {
      background-color: white;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    footer {
      background-color: #222;
      color: white;
      text-align: center;
      padding: 30px 20px;
    }

    @media (max-width: 600px) {
      header {
        flex-direction: column;
        align-items: flex-start;
      }
      nav {
        margin-top: 10px;
      }
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">NSS NSUT</div>
    <nav>
      <a href="#about">About</a>
      <a href="#events">Events</a>
      <a href="#team">Team</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h1>National Service Scheme</h1>
    <p>Serving the community with passion and dedication - NSS NSUT empowers youth to make a difference.</p>
  </section>

  <section class="section" id="about">
    <h2>About Us</h2>
    <p>The NSS unit of NSUT fosters social responsibility among students by organizing various community service programs, awareness campaigns, and events that contribute towards nation-building.</p>
  </section>

  <section class="section" id="events">
    <h2>Recent Events</h2>
    <div class="card-container">
      <div class="card">
        <h3>Blood Donation Camp</h3>
        <p>Organized a successful blood donation drive with over 200 donors participating.</p>
      </div>
      <div class="card">
        <h3>Swachh Bharat Abhiyan</h3>
        <p>Cleanliness drive conducted across campus and nearby areas promoting hygiene awareness.</p>
      </div>
      <div class="card">
        <h3>Tree Plantation</h3>
        <p>Planted over 500 saplings to promote environmental sustainability.</p>
      </div>
    </div>
  </section>

  <section class="section" id="team">
    <h2>Meet Our Team</h2>
    <p>Our dedicated volunteers and coordinators work tirelessly to organize impactful programs and contribute meaningfully to society.</p>
  </section>

  <section class="section" id="contact">
    <h2>Contact Us</h2>
    <p>Email: nss@nsut.ac.in | Phone: +91 9876543210</p>
  </section>

  <footer>
    <p>&copy; 2025 NSS NSUT. All rights reserved.</p>
  </footer>
</body>
</html>
