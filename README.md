<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sweet Delight Bakery</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
<style>
body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background-color: #fff8f0;
    color: #333;
}

header {
    background: url('https://images.unsplash.com/photo-1509440159596-0249088772ff') no-repeat center center/cover;
    height: 90vh;
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    text-align: center;
}

header h1 {
    font-size: 3.5rem;
    background-color: rgba(0,0,0,0.5);
    padding: 20px;
    border-radius: 10px;
}

nav {
    background-color: #d2691e;
    padding: 15px;
    text-align: center;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    font-weight: 500;
}

section {
    padding: 50px 10%;
    text-align: center;
}

.products {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}

.product-card {
    background: white;
    border-radius: 10px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    overflow: hidden;
    transition: 0.3s;
}

.product-card:hover {
    transform: scale(1.05);
}

.product-card img {
    width: 100%;
    height: 250px;
    object-fit: cover;
}

.product-card h3 {
    margin: 15px 0;
}

footer {
    background-color: #d2691e;
    color: white;
    padding: 20px;
    text-align: center;
}
</style>
</head>

<body>

<nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
</nav>

<header id="home">
    <h1>Sweet Delight Bakery</h1>
</header>

<section id="about">
    <h2>About Us</h2>
    <p>Welcome to Sweet Delight Bakery! We bake fresh bread, cakes, and pastries every day using the finest ingredients. Taste the love in every bite!</p>
</section>

<section id="products">
    <h2>Our Specialties</h2>
    <div class="products">
        <div class="product-card">
            <img src="https://images.unsplash.com/photo-1542826438-bd32f43d626f" alt="Chocolate Cake">
            <h3>Chocolate Cake</h3>
        </div>

        <div class="product-card">
            <img src="https://images.unsplash.com/photo-1504754524776-8f4f37790ca0" alt="Fresh Bread">
            <h3>Fresh Bread</h3>
        </div>

        <div class="product-card">
            <img src="https://images.unsplash.com/photo-1486427944299-d1955d23e34d" alt="Cupcakes">
            <h3>Cupcakes</h3>
        </div>
    </div>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <p>Email: info@sweetdelight.com</p>
    <p>Phone: +123 456 7890</p>
</section>

<footer>
    <p>© 2026 Sweet Delight Bakery | Made with ❤️</p>
</footer>

</body>
</html>
