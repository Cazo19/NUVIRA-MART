<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Nuvira Mart</title>
<style>
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background: #fff8f0;
    margin: 0; padding: 0;
    color: #3a3a3a;
  }
  header {
    background: #b8860b; /* dark gold */
    padding: 1rem 2rem;
    color: white;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  header h1 {
    margin: 0;
    font-weight: 700;
    font-size: 1.8rem;
    letter-spacing: 2px;
  }
  nav a {
    color: white;
    text-decoration: none;
    margin-left: 1.5rem;
    font-weight: 600;
  }
  nav a:hover {
    text-decoration: underline;
  }
  main {
    padding: 2rem;
    max-width: 1100px;
    margin: auto;
  }
  h2 {
    color: #b8860b;
  }
  .products {
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(220px,1fr));
    gap: 1.5rem;
    margin-top: 1rem;
  }
  .product-card {
    border: 1px solid #ddd;
    border-radius: 8px;
    overflow: hidden;
    background: white;
    box-shadow: 0 0 8px rgb(184 134 11 / 0.1);
  }
  .product-card img {
    width: 100%;
    height: 180px;
    object-fit: cover;
  }
  .product-info {
    padding: 0.8rem 1rem;
  }
  .product-info h3 {
    margin: 0;
    font-size: 1.1rem;
  }
  .product-info p {
    margin: 0.5rem 0 1rem;
    color: #666;
    font-size: 0.9rem;
  }
  .product-info button {
    background: #b8860b;
    color: white;
    border: none;
    padding: 0.5rem 1rem;
    border-radius: 20px;
    cursor: pointer;
    font-weight: 600;
    transition: background 0.3s ease;
  }
  .product-info button:hover {
    background: #a17307;
  }
  footer {
    text-align: center;
    padding: 1rem 2rem;
    background: #b8860b;
    color: white;
    margin-top: 3rem;
  }
</style>
</head>
<body>

<header>
  <h1>Nuvira Mart</h1>
  <nav>
    <a href="#">Home</a>
    <a href="#">Seller Login</a>
    <a href="#">Register</a>
    <a href="#">Cart</a>
  </nav>
</header>

<main>
  <h2>Featured Products</h2>
  <div class="products">
    <div class="product-card">
      <img src="https://images.unsplash.com/photo-15197

