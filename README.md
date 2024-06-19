<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SkyMarket</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        header {
            background-color: #2d2d2d;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: space-around;
            padding: 10px 0;
            background-color: #4caf50;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px;
        }
        .container {
            padding: 20px;
        }
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }
        .product {
            border: 1px solid #ccc;
            border-radius: 5px;
            padding: 15px;
            text-align: center;
        }
        .product img {
            max-width: 100%;
            height: auto;
        }
        footer {
            background-color: #2d2d2d;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>SkyMarket</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#products">Products</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <h2>Featured Products</h2>
        <div class="products">
            <div class="product">
                <img src="https://via.placeholder.com/150" alt="Product 1">
                <h3>Product 1</h3>
                <p>$19.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/150" alt="Product 2">
                <h3>Product 2</h3>
                <p>$29.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/150" alt="Product 3">
                <h3>Product 3</h3>
                <p>$39.99</p>
                <button>Add to Cart</button>
            </div>
            <!-- Add more products as needed -->
        </div>
    </div>
    <footer>
        <p>&copy; 2024 SkyMarket. All rights reserved.</p>
    </footer>
</body>
</html>

