# clean-water-landing
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Charity Water Landing</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <!-- Header -->
  <header class="header">
    <div class="logo">Charity:Water</div>
    <button class="donate-btn">Donate Now</button>
  </header>

  <!-- Hero Section -->
  <section class="hero">

    <!-- Left Content -->
    <div class="hero-content">
      <h1>
        Give Clean Water in Seconds.
        See the Impact for Years.
      </h1>

      <p>
        Donate in seconds and see how your gift brings clean water and
        real change to communities in need.
      </p>

      <div class="subscribe-box">
        <input type="text" placeholder="HELLO IT'S BRI">
        <button>Subscribe</button>
      </div>
    </div>

    <!-- Right Image -->
    <div class="hero-image">
      <img src="images/hero.jpg" alt="Water well">
    </div>

  </section>

</body>
</html>

/* Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}

body {
  background: #f4f4f4;
}

/* Header */
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 40px;
  background: white;
}

.logo {
  font-weight: bold;
  font-size: 20px;
}

.donate-btn {
  background: #f7931e;
  color: white;
  border: none;
  padding: 10px 18px;
  border-radius: 6px;
  cursor: pointer;
}

/* Hero Section */
.hero {
  display: flex;
  min-height: 80vh;
}

.hero-content {
  width: 50%;
  padding: 80px 60px;
  background: #ead4a2;
}

.hero-content h1 {
  font-size: 42px;
  color: #203864;
  margin-bottom: 20px;
  line-height: 1.2;
}

.hero-content p {
  color: #444;
  margin-bottom: 30px;
}

/* Subscribe Box */
.subscribe-box {
  display: flex;
  background: white;
  border-radius: 10px;
  overflow: hidden;
  max-width: 450px;
}

.subscribe-box input {
  flex: 1;
  padding: 15px;
  border: none;
  outline: none;
}

.subscribe-box button {
  background: #f7931e;
  color: white;
  border: none;
  padding: 15px 25px;
  cursor: pointer;
}

/* Hero Image */
.hero-image {
  width: 50%;
}

.hero-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
