# task1-octanet
octanet web development task 1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A franchise of japanese food</title>
    <link rel="stylesheet" href="style.css">
    
</head>
<body>
    <header>
        <nav>
            <div class="logo"> chingsChineseFood</div>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#menu">Menu</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <div class="hero">
            <h1>Welcome to Our Restaurant</h1>
            <p>Experience the finest chinese food</p>
            <a href="#menu" class="btn">View Menu</a>
        </div>
    </section>

    <section id="menu">
        <h2>Our Menu</h2>
        <div class="menu-items">
            <div class="menu-item">
                <h3>veg noodles/non veg noodles</h3>
                <p>noodles made with best quality of items and our resturants special spices</p>
                <p>RS.190</p>
            </div>
            <div class="menu-item">
                <h3>spring roll</h3>
                <p>best quality spring roll made with good quality items and serves with two kinds of sauce </p>
                <p>Rs.80</p>
            </div>
            <div class="menu-item">
                <h3>nonveg soup/veg soup</h3>
                <p>best item of our restaurant </p>
                <p>RS.120</p>
                </div>
        
            
        </div>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>We are a family-owned restaurant that has been serving delicious food for over 20 years. Our mission is to provide best chinese items  for our guests.</p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name">
            <label for="email">Email:</label>
            <input type="email" id="email" name="email">
            <label for="message">Message:</label>
            <textarea id="message" name="message"></textarea>
            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 chings chinese food All rights reserved.</p>
    </footer>
</body>
</html>
/*css part*/
body{

    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    background: #333;
    color: #fff;
    padding: 1em 0;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 2em;
}

nav .logo {
    font-size: 1.5em;
}

nav ul {
    list-style: none;
    display: flex;
    margin: 0;
    padding: 0;
}

nav ul li {
    margin-left: 2em;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

.hero {
    background: url('restaurant.jpg') no-repeat center center/cover;
    color: #fff;
    text-align: center;
    padding: 8em 0;
}

.hero h1 {
    font-size: 3em;
    margin: 0;
}

.hero p {
    font-size: 1.5em;
}

.hero .btn {
    background: #e67e22;
    color: #fff;
    padding: 0.5em 1em;
    text-decoration: none;
    margin-top: 1em;
    display: inline-block;
}

section {
    padding: 4em 2em;
    text-align: center;
}

.menu-items {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    color: #e67e22;
}

.menu-item {
    border: 1px solid #ddd;
    padding: 1em;
    margin: 1em;
    width: 200px;
}

form {
    display: flex;
    flex-direction: column;
    max-width: 400px;
    margin: 0 auto;
}

form label {
    margin-top: 1em;
}

form input, form textarea {
    padding: 0.5em;
    margin-top: 0.5em;
}

form button {
    background:yellowgreen;
    color:oldlace;
    border: none;
    padding: 1em;
    margin-top: 1em;
    cursor: pointer;
}

footer {
    background: #333;
    color: black;
    text-align: center;
    padding: 1em 0;
    margin-top: 2em;
}





