# Project Responsive Web Design using Bootstrap
# Date:5/12/2024
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
Home Page:
```
  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Car Showcase</title>
    <style>
       .featured-cars {
  background-color: #f9f9f9;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 40px 20px;
}

.featured-cars h2 {
  font-size: 28px;
  margin-bottom: 20px;
  color: #333;
}

.car-grid {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 20px;
}

.car {
  width: 300px;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 8px;
  padding: 15px;
  text-align: center;
}

.car img {
  width: 100%;
  height: auto;
  border-radius: 5px;
}

.car h3 {
  font-size: 20px;
  margin: 10px 0;
}

.car p {
  font-size: 14px;
  color: #666;
}

/* Center alignment for the why-choose-us section */
.why-choose-us {
  background-color: #007bff;
  color: white;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 40px 20px;
}

.why-choose-us h2 {
  font-size: 28px;
  margin-bottom: 20px;
}

.why-choose-us ul {
  list-style: none;
  padding: 0;
  font-size: 16px;
  line-height: 1.8;
  text-align: center;
}

.why-choose-us ul li {
  margin-bottom: 10px;
}


    </style>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

<!-- Navigation Bar -->
<nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
        <a class="navbar-brand d-flex align-items-center" href="#">
            <img src="c:\Users\admin\Pictures\Saved Pictures\logo.jpg" alt="Elite Motors Logo" style="width: 50px; height: 50px; margin-right: 10px;">
            <h1 style="text-align: center; margin: 0;">Elite Motors</h1>
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item">
                    <a class="nav-link" href="C:\Users\admin\tt\HTML Codes\about project.html">About</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="C:\Users\admin\tt\HTML Codes\portfolio.html">Portfolio</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="C:\Users\admin\tt\HTML Codes\contact.html">Contact</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="C:\Users\admin\tt\HTML Codes\signin.html">Sign In</a>
                </li>
            </ul>
        </div>
    </div>
</nav>

<div class="container text-center my-5">
    <h1>Welcome to Car Showcase</h1>
    <p class="lead">Discover the latest and greatest cars</p>
    <a href="C:\Users\admin\tt\HTML Codes\portfolio.html" class="btn btn-primary">Explore Cars</a>
</div>
<section class="featured-cars">
    <div class="container">
      <h2>Featured Cars</h2>
      <div class="car-grid">
        <div class="car">
          <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-27 100732.png" alt="Luxury Sedan">
          <h3>Luxury Sedan</h3>
          <p>Experience ultimate comfort and style with our premium sedans.</p>
        </div>
        <div class="car">
          <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-27 100947.png" alt="Sports Car">
          <h3>Sports Car</h3>
          <p>Unleash the thrill with our high-performance sports cars.</p>
        </div>
        <div class="car">
          <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-27 100902.png" alt="SUV">
          <h3>Luxury SUV</h3>
          <p>Explore the world in luxury and power with our SUVs.</p>
        </div>
      </div>
    </div>
  </section>
  
  <section class="why-choose-us">
    <div class="container">
      <h2>Why Choose Elite Motors?</h2>
      <ul>
        <li>Exceptional craftsmanship and attention to detail.</li>
        <li>State-of-the-art technology for a superior driving experience.</li>
        <li>Unmatched customer service and global presence.</li>
        <li>Commitment to sustainability with hybrid and electric models.</li>
      </ul>
    </div>
  </section>-
  


<footer class="bg-dark text-white text-center py-3">
    <p class="mb-0">&copy; 2024 Tauqir Ahmed</p>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
About Us:
```
<html>
    <head>
        <title> About</title>
        <style>
            .content
            {
               
                text-align: center;
            }
        </style>
    </head>
    <body>
        <h1 style="text-align: center;"> Elite Motors</h1>
        <div class="content">
        <section id="about" class="py-5 bg-light">
            <div class="container text-center">
                <h2>About Us</h2>
                <p class="mt-3">Elite Motors is a premier luxury automotive brand renowned for its seamless blend of opulence, performance, and innovation. Established to cater to the discerning tastes of elite clientele, the company is celebrated for its exceptional craftsmanship, bespoke design options, and cutting-edge technology. Elite Motors vehicles are characterized by their sophisticated designs, premium materials, and meticulous attention to detail, ensuring an unmatched driving experience. The brand offers a diverse lineup of high-performance sports cars, refined sedans, and versatile SUVs, each engineered to deliver power and precision. Staying at the forefront of automotive innovation, Elite Motors integrates advanced features like AI-assisted driving, state-of-the-art infotainment systems, and sustainable electric powertrains. With a strong commitment to sustainability, the company embraces eco-friendly practices and offers hybrid and fully electric models, reflecting its vision for a greener future. Through bespoke customization services, Elite Motors allows customers to create vehicles that embody their unique preferences, ensuring exclusivity and personalization. With a global presence and a dedication to exceptional service, Elite Motors continues to set new benchmarks in luxury mobility, appealing to those who demand excellence in every aspect of life.</p>
            </div>
        </section>
       </div>
    </body>
</html>
```
Gallery :
```
<html>
    <head>
        <title> Portfolio</title>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    </head>
    <body>
       <section id="portfolio" class="py-5">
        <div class="container">
          <h2 class="text-center">Car Gallery</h2>
           <div class="row mt-4">
            <div class="col-md-4">
                <div class="card">
                    <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-27 094538.png" class="card-img-top" alt="Car 1">
                    <div class="card-body">
                        <h5 class="card-title">Elegant Cruiser</h5>
                        <p class="card-text">A sleek and polished sedan with a focus on comfort and style</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-27 094549.png" class="card-img-top" alt="Car 2">
                    <div class="card-body">
                        <h5 class="card-title">Prestige Pioneer</h5>
                        <p class="card-text">A versatile and stylish luxury crossover.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-27 094558.png" class="card-img-top" alt="Car 3">
                    <div class="card-body">
                        <h5 class="card-title">Chic Roadster</h5>
                        <p class="card-text">A convertible sports car, perfect for an open-road experience.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-27 094608.png" class="card-img-top" alt="Car 3">
                    <div class="card-body">
                        <h5 class="card-title">Supreme Racer </h5>
                        <p class="card-text">A performance-focused luxury car with aggressive features.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-27 094617.png" class="card-img-top" alt="Car 3">
                    <div class="card-body">
                        <h5 class="card-title">Opulent Glide </h5>
                        <p class="card-text">A premium sedan showcasing timeless sophistication.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-27 094626.png" class="card-img-top" alt="Car 3">
                    <div class="card-body">
                        <h5 class="card-title">Grand Conqueror </h5>
                        <p class="card-text">A bold and commanding luxury sedan.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-27 095042.png" class="card-img-top" alt="Car 3">
                    <div class="card-body">
                        <h5 class="card-title">Velocity Phantom</h5>
                        <p class="card-text">A sharp sports car with aerodynamic lines and a bold stance.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-27 095157.png" class="card-img-top" alt="Car 3">
                    <div class="card-body">
                        <h5 class="card-title">Regal Voyager</h5>
                        <p class="card-text">A luxurious touring car, blending power with elegance.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-27 094701.png" class="card-img-top" alt="Car 3">
                    <div class="card-body">
                        <h5 class="card-title">Majestic Explorer</h5>
                        <p class="card-text">A high-end SUV designed for luxury and off-road capability.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>
</body>
</html>
```
Contact:
```
<html>
<head>
    <title>Contact Us</title>
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
            font-family: Arial, sans-serif;
        }

        .navbar-logo-container {
            display: flex;
            justify-content: center; /* Centers the logo horizontally */
            align-items: center; /* Centers the logo vertically */
            height: 20vh; /* Sets the height of the logo container */
        }

        .navbar-brand {
            display: flex;
            align-items: center;
            text-align: center;
            font-size: 1.5rem;
            text-decoration: none;
        }

        .navbar-brand img {
            margin-right: 10px; 
            border-radius: 50%; 
        }

        .contact-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            align-items: flex-start; /* Align items at the top */
            background-color: white;
            padding: 40px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            max-width: 900px;
            width: 100%;
            margin: auto;
            gap: 20px; /* Adds space between flex children */
        }

        .contact-form, .contact-info {
            flex: 1;
            margin: 10px;
        }

    </style>
</head>
<body>
    <h1 style="text-align: center;"> Elite Motors</h1>

    <div class="navbar-logo-container">
        <a class="navbar-brand mx-auto d-flex align-items-center" href="#">
            <img src="C:\Users\admin\Pictures\Saved Pictures\logo.jpg" alt="Logo" width="80" height="80">
        </a>
    </div>

    <div class="contact-container">
        <div class="contact-form">
            <h3 class="mb-4">Send Us a Message</h3>
            <form>
                <div class="form-group">
                    <label for="name">Full Name</label>
                    <input type="text" class="form-control" id="name" placeholder="Enter your full name" required>
                </div>
                <div class="form-group">
                    <label for="email">Email Address</label>
                    <input type="email" class="form-control" id="email" placeholder="Enter your email" required>
                </div>
                <div class="form-group">
                    <label for="message">Your Message</label>
                    <textarea class="form-control" id="message" rows="5" placeholder="Write your message" required></textarea>
                </div>
                <button type="submit" class="btn btn-primary btn-block">Submit</button>
            </form>
        </div>

        <div class="contact-info">
            <h3 class="mb-4">Get in Touch</h3>
            <p><strong>Phone:</strong> 9845754787</p>
            <p><strong>Email:</strong> elitemotors245@gmail.com</p>
            <h4 class="mt-4">Follow Us</h4>
          
        </div>
    </div>
</body>
</html>
```
Sign in:
```
<html>
    <head>
        <title> signin</title>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    </head>
    <body>
<section id="signin" class="py-5">
    <div class="container">
        <h2 class="text-center">Sign In</h2>
        <form class="mt-4">
            <div class="mb-3">
                <label for="email" class="form-label">Email address</label>
                <input type="email" class="form-control" id="email" placeholder="Enter your email">
            </div>
            <div class="mb-3">
                <label for="password" class="form-label">Password</label>
                <input type="password" class="form-control" id="password" placeholder="Enter your password">
            </div>
            <button type="submit" class="btn btn-primary">Sign In</button>
        </form>
        <p class="mt-3">Don't have an account? <a href="#signup">Sign Up</a></p>
    </div>
</section>
</body>
</html>
```
# OUTPUT:

![Screenshot 2024-12-27 102023](https://github.com/user-attachments/assets/58b55daa-8be5-4185-b848-c5428b3200f3)

![Screenshot 2024-12-27 103100](https://github.com/user-attachments/assets/8a960f11-fe42-4db6-8d7e-d2f044ca7dc9)

![Screenshot 2024-12-27 102911](https://github.com/user-attachments/assets/389e001d-b33a-48a2-928c-bab39d24da9a)

![Screenshot 2024-12-27 102942](https://github.com/user-attachments/assets/f7b37435-b58b-417c-8db8-3a117a05e640)

![Screenshot 2024-12-27 103003](https://github.com/user-attachments/assets/1feec641-da89-4116-ab36-849d6d7c5805)

# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
