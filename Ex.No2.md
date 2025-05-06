![image](https://github.com/user-attachments/assets/e890c695-6920-4f2f-a7cd-792f07ee199c)# Ex02 Commercial Website
## Date:

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
Created by,
Name: Bakkiyalakshmi E.
Regno.: 212223220012

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Book Store</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
we(boo)
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
    }

    /* Navbar */
    nav {
      background-color: #333;
      color: rgb(229, 124, 203);
      padding: 1rem;
    }

    .nav-container {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .nav-container ul {
      display: flex;
      list-style-type: none;
    }

    .nav-container ul li {
      margin: 0 15px;
    }

    .nav-container ul li a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    .nav-container ul li a:hover {
      text-decoration: underline;
    }

  
.hero {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background: url('.vscode/4.jpeg') center/cover no-repeat;
  color: white;
  text-align: center;
}


    .hero h1 {
      font-size: 3rem;
      margin-bottom: 20px;
    }

    .hero p {
      font-size: 1.5rem;
    }

    .book-section {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      padding: 2rem;
      background-color: #f4f4f4;
    }

    .book {
      flex: 1 1 300px;
      margin: 1rem;
      padding: 1.5rem;
      background-color: white;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
      text-align: center;
    }

    .book img {
      width: 200px; 
      height: 300px; 
      object-fit: cover;
      border-radius: 8px;
    }

    .book h3 {
      margin: 1rem 0;
      font-size: 1.5rem;
    }

    .book p {
      color: #555;
      margin-bottom: 1rem;
    }

    .book .price {
      font-size: 1.25rem;
      font-weight: bold;
      color: #333;
    }

    /* Footer */
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 1rem;
    }

    footer p {
      font-size: 1rem;
    }

    @media (max-width: 768px) {
      .nav-container {
        flex-direction: column;
        align-items: flex-start;
      }

      .hero h1 {
        font-size: 2.5rem;
      }

      .book-section {
        flex-direction: column;
        align-items: center;
      }
    }

  </style>
</head>
<body>

  <nav>
    <div class="nav-container">
      <div class="logo">
        <a href="#" style="color:white; font-size: 1.5rem; font-weight: bold;">BookStore</a>
      </div>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#books">Books</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </div>
  </nav>

  <section class="hero" id="home">
    <div>
      <h1>Welcome to BookStore</h1>
      <p>Discover your next great read!</p>
    </div>
  </section>


  <section class="book-section" id="books">
    <div class="book">
      <img src=".vscode/we(3).jpg" alt="Book 1">
      <h3>A Man Called Ove</h3>
      <p>Brief description of the book.</p>
      <p class="price">$11.01</p>
    </div>
    <div class="book">
      <img src=".vscode/1.jpeg" alt="Book 2">
      <h3>Feeling Good</h3>
      <p>Brief description of the book.</p>
      <p class="price">$30.00</p>
    </div>
    <div class="book">
      <img src=".vscode/w(2).jpeg" alt="Book 3">
      <h3>Just Feel Good</h3>
      <p>Brief description of the book.</p>
      <p class="price">$11.18</p>
    </div>
  </section>

  
  <footer>
    <p>&copy; 2025 BookStore. All Rights Reserved.</p>
    <p>Name: Bakkiyalakshmi E | Reg No: 212223220012</p>
  </footer>

</body>
</html>

```

## OUTPUT
![image](https://github.com/user-attachments/assets/b98c10c6-e2a1-4417-b52f-bcee220ccb73)

![image](https://github.com/user-attachments/assets/ec59e9bb-bdf5-4d18-834e-88f5d61cbd1e)

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
