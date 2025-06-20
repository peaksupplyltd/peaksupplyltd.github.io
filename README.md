<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Peak Supply Ltd - Product Catalog</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f6f8;
      margin: 0;
      padding: 0 20px;
    }
    h1, h2 {
      text-align: center;
      color: #2a3b4c;
    }
    .product-card {
      background: white;
      border-radius: 12px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      padding: 20px;
      margin: 20px auto;
      max-width: 800px;
    }
    .product-card img {
      max-width: 100%;
      height: auto;
      border-radius: 10px;
    }
    .product-card h3 {
      color: #2a3b4c;
    }
    .price {
      color: #00539b;
      font-weight: bold;
      font-size: 1.1em;
    }
    .quantity {
      margin-top: 10px;
    }
    .quantity input {
      width: 60px;
      padding: 5px;
      font-size: 1em;
    }
    .description {
      margin-top: 10px;
    }
  </style>
</head>
<body>
  <h1>Peak Supply Ltd</h1>
  <p style="text-align:center;">Your trusted source for mobility and bathroom safety products</p>

  <section id="walkers">
    <h2>Walkers</h2>
    <div class="product-card">
      <img src="https://dohomehealthcare.com/cdn/shop/files/knee-walker.webp?v=1681439913&width=1100" alt="Standard Knee Walker">
      <h3>Standard Knee Walker</h3>
      <p><strong>SKU:</strong> MHKW-STD</p>
      <p class="description">Sturdy knee walker with dual braking, foldable frame, and basket. Dependable choice for post-op and injury mobility.</p>
      <p class="price">CAD $239.99</p>
      <div class="quantity">
        <label>Units:</label>
        <input type="number" min="0" value="0">
      </div>
    </div>
  </section>

  <section id="wheelchairs">
    <h2>Wheelchairs</h2>
    <div class="product-card">
      <img src="https://dohomehealthcare.com/cdn/shop/files/lightweight-steel-wheelchair.jpg?v=1681439913&width=1100" alt="Lightweight Steel Wheelchair">
      <h3>Lightweight Steel Wheelchair</h3>
      <p><strong>SKU:</strong> MHWC1016</p>
      <p class="description">Durable powder-coated steel with flip-back desk arms, travel lite at 36–40 lbs. 300–350 lb capacity, easy-clean upholstery.</p>
      <p class="price">CAD $420.00</p>
      <div class="quantity">
        <label>Units:</label>
        <input type="number" min="0" value="0">
      </div>
    </div>
  </section>

</body>
</html>
  
