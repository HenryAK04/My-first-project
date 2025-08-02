<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>The chain plumbing solutions</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>The Chain Plumbing Solutions</h1>
    <input type="text" placeholder="Search for products...">
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">Cart 🛒</a>
    <a href="#"></a>
    <a href="#"></a>
    <a href="#"></a>
  </nav>

  <section class="products">
    <div class="product">
      <img src="bendplain.jpg" alt="Product 1">
      <h3>bend plin</h3>
      <p>UGX 5,000</p>
      <button>Add to Cart</button>
    </div>

    <div class="product">
      <img src="gatevalve ¾.jpg" alt="Product 2">
      <h3>Gate Valve</h3>
      <p>UGX 20,000</p>
      <button>Add to Cart</button>
    </div>
    
    <div class="product">
      <img src="benddoor.jpg" alt="Product 3">
      <h3>Benddoor</h3>
      <p>UGX 8,000</p>
      <button>Add to Cart</button>
   </div>
    
    <div class="product">
      <img src="panconnector.jpg" alt="Product 4">
      <h3>Pan connector</h3>
      <p>UGX 15,000</p>
      <button>Add to Cart</button>
    </div>
    

    <div class="product">
      <img src="reducingbush.jpg" alt="Product 2">
      <h3>reducing bush 4_2</h3>
      <p>UGX 5,000</p>
      <button>Add to Cart</button>
    </div>

   <div class="product">
      <img src="bend.jpg" alt="Product 2">
      <h3>bend 2inch</h3>
      <p>UGX 3,000</p>
      <button>Add to Cart</button>
    </div>
 
   <div class="product">
      <img src="soapdish.jpg" alt="Product 2">
      <h3>soap dish</h3>
      <p>UGX 15,000</p>
      <button>Add to Cart</button>
    </div>

   <div class="product">
      <img src="PVCsolvent.jpg" alt="Product 2">
      <h3>Solvent</h3>
      <p>UGX 5,000</p>
      <button>Add to Cart</button>
    </div>
 
   <div class="product">
      <img src="magicwaste.jpg" alt="Product 2">
      <h3>Magic waste</h3>
      <p>UGX 10,000</p>
      <button>Add to Cart</button>
    </div>
 
   <div class="product">
      <img src="union.jpg" alt="Product 2">
      <h3>Union ¾</h3>
      <p>UGX 5,000</p>
      <button>Add to Cart</button>
    </div>

   <div class="product">
      <img src="telephoneshower.jpg" alt="Product 2">
      <h3>telephone shower</h3>
      <p>UGX 25,000</p>
      <button>Add to Cart</button>
    </div>
 
   <div class="product">
     <img src="cistern.jpg" alt="Product 2">
      <h3>Cistern</h3>
     <p>UGX 55,000</p>
     <button>Add to cart</button>
    </div>
 
   <div class="product">
     <img src="silicone.jpg" alt="Product 2">
      <h3>silicone</h3>
     <p>UGX 10,000</p>
     <button>Add to cart</button>
    </div>
   <div class="product">
     <img src="tplain.jpg" alt="Product 2">
      <h3>PVC T Plain</h3>
     <p>UGX 3,000</p>
     <button>Add to cart</button>
    </div>

    <div class="product">
     <img src="showerpipe.jpg" alt="Product 2">
      <h3>shower pipe</h3>
     <p>UGX 10,000</p>
     <button>Add to cart</button>
    </div>
    
    <div class="product">
     <img src="push.jpg" alt="Product 2">
      <h3>Pish</h3>
     <p>UGX 6,000</p>
     <button>Add to cart</button>
    </div>
    
    <div class="product">
     <img src="tplain8.jpg" alt="Product 2">
      <h3>PVC T Plain</h3>
     <p>UGX 8,000</p>
     <button>Add to cart</button>
    </div>
    
     <div class="product">
     <img src="showerhead10.jpg" alt="Product 2">
      <h3>Shower head</h3>
     <p>UGX 20,000</p>
     <button>Add to cart</button>
    </div>

    <!-- Add more products here -->
  </section>

  <footer>
    <p>&copy; 2025 MyShop - All Rights Reserved</p>
     <a class="buy-btn" href="https://wa.me/256707580735">Contact on WhatsApp</a>
  </footer>
</body>
</html># My-first-project

body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background: #f2f2f2;
}

header {
  background: #129dba;
  color: white;
  padding: 10px;
  text-align: center;
}

header input {
  margin-top: 10px;
  padding: 8px;
  width: 80%;
  max-width: 400px;
}

nav {
  display: flex;
  justify-content: space-around;
  background: #333;
  padding: 10px;
}

nav a {
  color: white;
  text-decoration: none;
}

.products {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 15px;
  padding: 20px;
}

.product {
  background: white;
  padding: 10px;
  text-align: center;
  border-radius: 5px;
}

.product img {
  width: 100%;
  height: auto;
}

.product button {
  background: #142ddb;
  color: white;
  padding: 8px;
  border: none;
  cursor: pointer;
}

footer {
  text-align: center;
  padding: 10px;
  background: #333;
  color: white;
}
