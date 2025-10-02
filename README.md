# Ex.07 Restaurant Website
## Date:02.10.2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Restaurant - Home</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <header>
    <h1>SB RESTAURANT</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="contact.html">Contact</a>
      <a href="admin.html">Administration</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Welcome to SB Restaurant</h2>
    <p>Enjoy the finest dishes made with love "Your table is calling"</p>
  </section>

  <section class="dishes">
    <h2>Our Special Dishes</h2>
    <div class="dish-grid">
      <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-01 195155.png" alt="Dish 1">
      <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-02 142148.png" alt="Dish 2">
      <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-02 142626.png" alt="Dish 3">
      <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-01 200439.png" alt="Dish 4">
      <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-02 132114.png" alt="Dish 5">
      <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-01 201404.png" alt="Dish 6">
    </div>
  </section>

  <footer>
    <p>© 2025 SB Restaurant</p>
  </footer>
</body>
</html>

menu.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-5">
  <title>Restaurant - Menu</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
<header>
  <h1>SB Restaurant</h1>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact</a>
    <a href="admin.html">Administration</a>
  </nav>
</header>

<section class="menu">
  <h2>Our Menu</h2>
  <ul>
    <li>Grilled Chicken - 320</li> <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-01 204729.png"> <p>Grilled chicken is chicken cooked over direct heat on a grill, resulting in a seared, charred exterior and a moist interior. It is often seasoned with herbs, spices, or marinades before cooking, creating a flavorful dish that can be served as a main course, side dish, or appetizer. Grilled chicken is a versatile and popular dish known for being a good source of lean protein.  </p>
    <li>Pasta Alfredo - 450</li> <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-01 205355.png"> <p>The Alfredo Pasta is an Italian pasta dish made using fresh pasta, vegetables, chicken pieces combined with butter, cream and cheese. As the cheese melts, it results in a creamy, rich cheese sauce that coats the pasta. It is without a doubt one of the most delicious and simple dishes to prepare at home.</p>
    <li>Paneer Butter Masala - 250</li> <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-01 210535.png"> <p>Paneer butter masala is a rich and creamy North Indian curry featuring tender cubes of paneer (Indian cottage cheese) simmered in a silky tomato and cashew-based sauce. It is known for its luxurious texture and harmonious blend of flavors, making it a favorite dish in Indian restaurants and homes worldwide</p>
    <li>Veggie Pizza - 320</li> <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-01 222416.png"> <p>Pizza is a popular Italian dish consisting of a flattened bread dough base topped with tomato sauce and cheese, often with additional ingredients like vegetables and meats, then baked at a high temperature. The concept is a flat, open-faced baked pie that is customizable with a wide variety of toppings and sauces, resulting in diverse flavors and textures.  </p>
    <li>Chicken Biryani - 280</li> <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-01 222633.png"> <p>Chicken Biryani is a flavorful one-pot dish originating from the Indian subcontinent, made by layering marinated chicken with aromatic basmati rice, spices, and sometimes vegetables like potatoes, then slow-cooking it using the dum pukht ("steam-cooked") method in a sealed pot. The chicken is marinated in yogurt, ginger-garlic paste, and a complex blend of whole and ground spices, infusing it with rich flavors and ensuring tenderness.</p>
    <li>Caesar Salad - 320</li> <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-01 222821.png"> <p>A Caesar salad (also spelled Cesar, César and Cesare), also known as Caesar's salad, is a green salad of romaine lettuce and croutons dressed with lemon juice (or lime juice), olive oil, eggs, Worcestershire sauce, anchovies, garlic, Dijon mustard, Parmesan and black pepper.</p>
    <li>Seafood Platter - 800</li> <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-01 223212.png"> <p>The classic seafood platter is a true crowd-pleaser. It typically includes an array of freshly shucked oysters, succulent steamed or chilled shrimp, tender crab legs, and a selection of dipping sauces such as tartar sauce, cocktail sauce, and mignonette</p>
    <li>Chocolate Cake - 120</li> <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-01 223442.png"> <p>A good cake has a soft and even crumb that feels light and melts smoothly in your mouth. When choosing a cake, look for: A fine and even crumb without large holes or dense patches. Softness that holds together without being dry or crumbly. A moist texture that feels fresh and delicate.</p>
    <li>Chicken noodles - 180</li> <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-01 223651.png"><p>Chicken noodles can describe both a comforting, hearty dish made with thick egg noodles in a creamy, rich broth with chicken and vegetables, as well as a flavorful, stir-fried Indo-Chinese dish of noodles, chicken, and vegetables with savory sauces. The dish type depends on whether it is referring to a soup or a noodle-based meal, with the former being a soup and the latter a stir-fry.  </p>
    <li>Burger - 100</li> <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-01 223832.png"> <p>A burger is a ground meat patty, most often beef, served between two halves of a sliced bun or roll, often with various condiments like ketchup, mustard, and mayonnaise, and toppings such as cheese, lettuce, tomato, onion, and pickles. It's a popular sandwich and main course dish, known for its versatility with diverse regional and international variations. </p>
    <li>Chicken Friedrice - 150</li> <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-01 200439.png"> <p>Chicken fried rice is a popular Asian-inspired rice dish made by stir-frying cooked rice, chicken, eggs, and vegetables like carrots and peas in a wok or pan, seasoned with soy sauce and other spices. It is a flavorful and versatile dish that can be enjoyed as a standalone meal, often made with leftover rice for best results.  </p>
    <li>Chilli Parotta - 180</li> <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-01 201404.png"> <p>Chilli parotta is one of the many flaky and crunchy parottas (although spicy) that South India is famous for. This semi-dry dish is made with torn pieces of parotta which are stir fried with onion and bell pepper. A touch of spices, sauces and herbs add the extra flavor.</p>
  </ul>
</section>

<footer>
  <p>© 2025 SB Restaurant</p>
</footer>
</body>
</html>

contact.html
!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Restaurant - Contact</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
<header>
  <h1> SB Restaurant</h1>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact</a>
    <a href="admin.html">Administration</a>
  </nav>
</header>

<section class="contact">
  <h2>Contact Us</h2>
  <p>📍 5/453 -1,Noel street, madurai</p>
  <p>📞 +91 8124184552</p>
  <p>📧 EMAIL : sbrest1902@gmail.com</p>
  <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-02 140846.png">
</section>

<footer>
  <p>© 2025 SB Restaurant</p>
</footer>
</body>
</html>

admin.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Admin Dashboard</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
<header>
  <h1>Admin Dashboard</h1>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact</a>
    <a href="admin.html">Logout</a>
  </nav>
</header>

<section class="dashboard">
  <h2>Available Dishes</h2>
  <ul>
    <li>Grilled Chicken</li>
    <li>Pasta Alfredo</li>
    <li>Paneer Butter Masala</li>
    <li>Veggie Pizza</li>
    <li>Chicken Biryani</li>
  </ul>

  <h2>Add New Dish</h2>
  <form>
    <input type="text" placeholder="Dish Name">
    <input type="text" placeholder="Price">
    <button type="submit">Add Dish</button>
  </form>

  <h2>Employees on Shift</h2>
  <ul>
    <li>PRANAV- chief Chef</li> <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-02 113600.png">
    <li>SARA - Waitress</li> <IMG SRC="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-02 113852.png">
    <li>SUZAN - Manager</li> <IMG SRC="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-02 113459.png">
    <li>JOHN - Chief Executive Chef</li> <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-02 113618.png">
    <li>MANASA - Executive Chef</li> <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-02 113420.png">
    <li>PREETHI - Chief Chef</li> <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-02 113655.png">
  </ul>
</section>

<footer>
  <p>© 2025 SB Restaurant</p>
</footer>
</body>
</html>

admin-dashboard.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Admin Dashboard</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
<header>
  <h1>Admin Dashboard</h1>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact</a>
    <a href="admin.html">Logout</a>
  </nav>
</header>

<section class="dashboard">
  <h2>Available Dishes</h2>
  <ul>
    <li>Grilled Chicken</li>
    <li>Pasta Alfredo</li>
    <li>Paneer Butter Masala</li>
    <li>Veggie Pizza</li>
    <li>Chicken Biryani</li>
  </ul>

  <h2>Add New Dish</h2>
  <form>
    <input type="text" placeholder="Dish Name">
    <input type="text" placeholder="Price">
    <button type="submit">Add Dish</button>
  </form>

  <h2>Employees on Shift</h2>
  <ul>
    <li>PRANAV- chief Chef</li> <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-02 113600.png">
    <li>SARA - Waitress</li> <IMG SRC="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-02 113852.png">
    <li>SUZAN - Manager</li> <IMG SRC="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-02 113459.png">
    <li>JOHN - Chief Executive Chef</li> <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-02 113618.png">
    <li>MANASA - Executive Chef</li> <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-02 113420.png">
    <li>PREETHI - Chief Chef</li> <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2025-10-02 113655.png">
  </ul>
</section>

<footer>
  <p>© 2025 SB Restaurant</p>
</footer>
</body>
</html>
```




## OUTPUT:
![alt text](<Screenshot 2025-10-02 155845.png>) 
![alt text](<Screenshot 2025-10-02 155348.png>) 
![alt text](<Screenshot 2025-10-02 155400.png>) 
![alt text](<Screenshot 2025-10-02 155413.png>) 
![alt text](<Screenshot 2025-10-02 155428.png>)
![alt text](<Screenshot 2025-10-02 155444.png>)
![alt text](<Screenshot 2025-10-02 155457.png>) 
![alt text](<Screenshot 2025-10-02 155806.png>) 
![alt text](<Screenshot 2025-10-02 155816.png>) 
![alt text](<Screenshot 2025-10-02 155826.png>) 
![alt text](<Screenshot 2025-10-02 155836.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
