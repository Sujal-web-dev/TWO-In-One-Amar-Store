<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>TWO IN ONE AMAR STORE</title>
<style>
  /* Modern, clean styling */
  @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap');
  body {
    margin: 0; padding: 0;
    font-family: 'Montserrat', sans-serif;
    background: #f5f7fa;
    color: #333;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
  }
  header {
    background-color: #0077cc;
    color: white;
    padding: 1rem 2rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
  }
  header h1 {
    margin: 0;
    font-weight: 700;
    font-size: 1.8rem;
  }
  header .store-info {
    font-size: 0.9rem;
    font-weight: 400;
    margin-left: 1rem;
    max-width: 400px;
  }
  nav {
    margin-top: 0.5rem;
    width: 100%;
    text-align: right;
  }
  nav button {
    background: transparent;
    border: 2px solid white;
    color: white;
    padding: 0.5rem 1rem;
    margin-left: 1rem;
    border-radius: 4px;
    font-weight: 600;
    cursor: pointer;
    transition: background 0.3s, color 0.3s;
    min-width: 100px;
  }
  nav button.active, nav button:hover {
    background: white;
    color: #0077cc;
  }
  main {
    flex-grow: 1;
    padding: 2rem;
    max-width: 1200px;
    margin: 0 auto;
    width: 100%;
  }
  /* Customer View */
  #customer-view {
    display: none;
  }
  #search-bar {
    margin-bottom: 1rem;
    display: flex;
    max-width: 400px;
  }
  #search-input {
    flex-grow: 1;
    padding: 0.5rem 1rem;
    border: 2px solid #0077cc;
    border-radius: 4px 0 0 4px;
    font-size: 1rem;
    outline: none;
  }
  #search-clear {
    background: #0077cc;
    border: none;
    color: white;
    cursor: pointer;
    padding: 0 1rem;
    font-size: 1.2rem;
    border-radius: 0 4px 4px 0;
    transition: background 0.3s;
  }
  #search-clear:hover {
    background: #005fa3;
  }
  #products-list {
    display: grid;
    grid-template-columns: repeat(auto-fill,minmax(250px,1fr));
    gap: 1.5rem;
  }
  .product-card {
    background: white;
    border-radius: 8px;
    box-shadow: 0 2px 10px rgb(0 0 0 / 0.1);
    display: flex;
    flex-direction: column;
    padding: 1rem;
    transition: box-shadow 0.3s;
  }
  .product-card:hover {
    box-shadow: 0 4px 15px rgb(0 0 0 / 0.2);
  }
  .product-image {
    width: 100%;
    height: 150px;
    object-fit: contain;
    border-radius: 6px;
    background: #e6e6e6;
    margin-bottom: 1rem;
  }
  .product-name {
    font-weight: 700;
    font-size: 1.1rem;
    margin-bottom: 0.25rem;
    flex-grow: 1;
  }
  .product-description {
    font-size: 0.9rem;
    color: #666;
    margin-bottom: 0.5rem;
    min-height: 40px;
  }
  .product-price {
    font-weight: 700;
    color: #0077cc;
    margin-bottom: 1rem;
  }
  .add-to-cart-btn {
    background-color: #0077cc;
    border: none;
    color: white;
    padding: 0.5rem;
    border-radius: 4px;
    font-weight: 600;
    cursor: pointer;
    transition: background-color 0.3s;
  }
  .add-to-cart-btn:hover {
    background-color: #005fa3;
  }

  /* Cart */
  #cart {
    margin-top: 2rem;
    background: white;
    padding: 1rem;
    border-radius: 8px;
    box-shadow: 0 2px 10px rgb(0 0 0 / 0.1);
  }
  #cart h2 {
    margin-top: 0;
  }
  #cart-items {
    list-style: none;
    padding: 0;
    margin: 1rem 0;
    max-height: 250px;
    overflow-y: auto;
  }
  #cart-items li {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0.4rem 0;
    border-bottom: 1px solid #eee;
  }
  #cart-items li:last-child {
    border-bottom: none;
  }
  .cart-item-name {
    font-weight: 600;
  }
  .cart-item-qty {
    margin: 0 1rem;
  }
  .cart-item-remove {
    color: #cc0000;
    cursor: pointer;
    font-weight: 600;
    border: none;
    background: none;
    font-size: 1rem;
  }
  #cart-total {
    font-weight: 700;
    font-size: 1.2rem;
    text-align: right;
    margin-top: 1rem;
  }
  #checkout-btn {
    background-color: #28a745;
    color: white;
    font-weight: 700;
    border: none;
    padding: 0.75rem 1.5rem;
    border-radius: 6px;
    cursor: pointer;
    margin-top: 1rem;
    float: right;
    transition: background-color 0.3s;
  }
  #checkout-btn:hover {
    background-color: #1e7e34;
  }

  /* Payment Modal */
  .modal {
    position: fixed;
    top: 0;
    left: 0;
    right:0;
    bottom:0;
    background: rgba(0,0,0,0.5);
    display: none;
    justify-content: center;
    align-items: center;
    z-index: 10;
  }
  .modal.active {
    display: flex;
  }
  .modal-content {
    background: white;
    border-radius: 10px;
    padding: 2rem;
    max-width: 400px;
    width: 90%;
    box-shadow: 0 2px 15px rgba(0,0,0,0.3);
    position: relative;
  }
  .modal-content h3 {
    margin-top: 0;
  }
  .modal-close {
    position: absolute;
    top: 0.5rem;
    right: 0.75rem;
    font-size: 1.5rem;
    font-weight: 700;
    color: #555;
    cursor: pointer;
    border: none;
    background: none;
  }
  .payment-methods button {
    width: 100%;
    padding: 0.75rem;
    margin: 0.5rem 0;
    border-radius: 6px;
    font-weight: 600;
    border: 2px solid #0077cc;
    background: white;
    color: #0077cc;
    cursor: pointer;
    transition: background-color 0.3s, color 0.3s;
  }
  .payment-methods button:hover {
    background-color: #0077cc;
    color: white;
  }
  form.payment-form {
    display: none;
    margin-top: 1rem;
  }
  form.payment-form.active {
    display: block;
  }
  form.payment-form label {
    display: block;
    margin: 0.5rem 0 0.25rem 0;
    font-weight: 600;
  }
  form.payment-form input {
    width: 100%;
    padding: 0.5rem;
    font-size: 1rem;
    border: 2px solid #ccc;
    border-radius: 4px;
    outline: none;
    box-sizing: border-box;
  }
  form.payment-form button.submit-payment {
    background-color: #0077cc;
    color: white;
    border: none;
    padding: 0.75rem;
    width: 100%;
    border-radius: 6px;
    font-weight: 700;
    margin-top: 1rem;
    cursor: pointer;
    transition: background-color 0.3s;
  }
  form.payment-form button.submit-payment:hover {
    background-color: #005fa3;
  }
  .payment-success {
    text-align: center;
    color: #28a745;
    font-weight: 700;
    margin-top: 1rem;
  }

  /* Owner View */
  #owner-view {
    display: none;
  }
  #owner-info {
    background: #e6f2ff;
    border: 2px solid #0077cc;
    border-radius: 8px;
    padding: 1rem 1.5rem;
    margin-bottom: 1rem;
    max-width: 600px;
  }
  #owner-info h2 {
    margin-top: 0;
    color: #0077cc;
  }
  #owner-info p {
    margin: 0.25rem 0;
    font-weight: 600;
    color: #004a80;
  }
  #owner-controls {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 1rem;
    margin-bottom: 1rem;
  }
  #owner-controls > div {
    flex: 1 1 300px;
    background: white;
    padding: 1rem;
    border-radius: 8px;
    box-shadow: 0 2px 10px rgb(0 0 0 / 0.1);
  }
  #product-form label {
    display: block;
    font-weight: 600;
    margin: 0.5rem 0 0.25rem 0;
  }
  #product-form input[type=text],
  #product-form input[type=number],
  #product-form textarea {
    width: 100%;
    padding: 0.5rem;
    font-size: 1rem;
    border-radius: 4px;
    border: 2px solid #ccc;
    outline: none;
    box-sizing: border-box;
  }
  #product-form textarea {
    resize: vertical;
    min-height: 60px;
  }
  #product-form button {
    margin-top: 1rem;
    background-color: #0077cc;
    color: white;
    border: none;
    padding: 0.75rem;
    cursor: pointer;
    border-radius: 6px;
    font-weight: 700;
    transition: background-color 0.3s;
    width: 100%;
  }
  #product-form button:hover {
    background-color: #005fa3;
  }
  #owner-products {
    margin-top: 1rem;
    background: white;
    padding: 1rem;
    border-radius: 8px;
    box-shadow: 0 2px 10px rgb(0 0 0 / 0.1);
  }
  #owner-products table {
    width: 100%;
    border-collapse: collapse;
  }
  #owner-products th, #owner-products td {
    border: 1px solid #ddd;
    padding: 0.5rem 0.75rem;
    text-align: left;
  }
  #owner-products th {
    background-color: #0077cc;
    color: white;
  }
  #owner-products td > button {
    margin-right: 0.5rem;
    border: none;
    padding: 0.3rem 0.6rem;
    border-radius: 4px;
    cursor: pointer;
    font-weight: 600;
    color: white;
    transition: background-color 0.3s;
  }
  #owner-products .btn-edit {
    background-color: #ffc107;
  }
  #owner-products .btn-edit:hover {
    background-color: #e0a800;
  }
  #owner-products .btn-delete {
    background-color: #dc3545;
  }
  #owner-products .btn-delete:hover {
    background-color: #bd2130;
  }
  #owner-orders {
    margin-top: 2rem;
    background: white;
    padding: 1rem;
    border-radius: 8px;
    box-shadow: 0 2px 10px rgb(0 0 0 / 0.1);
  }
  #owner-orders table {
    width: 100%;
    border-collapse: collapse;
  }
  #owner-orders th, #owner-orders td {
    border: 1px solid #ddd;
    padding: 0.5rem 0.75rem;
    text-align: left;
  }
  #owner-orders th {
    background-color: #17a2b8;
    color: white;
  }
  #owner-orders .order-status {
    font-weight: 700;
  }

  /* Responsive tweaks */
  @media (max-width: 600px) {
    #owner-controls {
      flex-direction: column;
    }
    nav button {
      margin: 0.25rem 0 0 0;
      min-width: auto;
      flex-grow: 1;
    }
  }
</style>
</head>
<body>
<header>
  <div style="display:flex; align-items: center; flex-wrap: wrap;">
    <h1>TWO IN ONE AMAR STORE</h1>
    <div class="store-info" aria-label="Store information">
      <div><strong>Owner:</strong> Sanjay Kumar</div>
      <div><strong>Mobile:</strong> 7488795956</div>
      <div><strong>Location:</strong> near pipal tree sultan nagar chas bokaro</div>
    </div>
  </div>
  <nav>
    <button id="btn-customer" class="active" aria-label="Switch to Customer View">Customer View</button>
    <button id="btn-owner" aria-label="Switch to Owner View">Owner View</button>
  </nav>
</header>
<main>
  <!-- Customer View -->
  <section id="customer-view" aria-label="Customer shopping area">
    <div id="search-bar" role="search">
      <input type="text" id="search-input" placeholder="Search products..." aria-label="Search products" />
      <button id="search-clear" aria-label="Clear search">&times;</button>
    </div>
    <div id="products-list" aria-live="polite"></div>
    <section id="cart" aria-label="Shopping cart">
      <h2>Your Cart</h2>
      <ul id="cart-items" aria-live="polite" aria-relevant="additions removals"></ul>
      <div id="cart-total" aria-live="polite">Total: ₹0.00</div>
      <button id="checkout-btn" aria-label="Proceed to checkout" disabled>Checkout</button>
    </section>
  </section>

  <!-- Owner View -->
  <section id="owner-view" aria-label="Owner management area">
    <section id="owner-info" aria-label="Owner and store details">
      <h2>Store Details</h2>
      <p><strong>Owner Name:</strong> Sanjay Kumar</p>
      <p><strong>PAN Card Number:</strong> GGMPK1159Q</p>
      <p><strong>Mobile Number:</strong> 7488795956</p>
      <p><strong>Location:</strong> near pipal tree sultan nagar chas bokaro</p>
    </section>
    <div id="owner-controls">
      <div>
        <h2>Add / Edit Product</h2>
        <form id="product-form" aria-label="Product form">
          <input type="hidden" id="product-id" />
          <label for="product-name">Product Name</label>
          <input type="text" id="product-name" required autocomplete="off" />
          <label for="product-description">Description</label>
          <textarea id="product-description" rows="3" required></textarea>
          <label for="product-price">Price (₹)</label>
          <input type="number" id="product-price" min="0" step="0.01" required />
          <label for="product-image">Image URL</label>
          <input type="text" id="product-image" placeholder="https://example.com/image.jpg" autocomplete="off" />
          <button type="submit" id="product-submit-btn">Add Product</button>
        </form>
      </div>
      <div id="owner-products" aria-label="Owner product list">
        <h2>Existing Products</h2>
        <table>
          <thead>
            <tr>
              <th>Name</th><th>Price (₹)</th><th>Description</th><th>Actions</th>
            </tr>
          </thead>
          <tbody id="owner-products-tbody"></tbody>
        </table>
      </div>
    </div>
    <section id="owner-orders" aria-label="Owner orders list">
      <h2>Orders</h2>
      <table>
        <thead>
          <tr>
            <th>Order ID</th><th>Items</th><th>Total (₹)</th><th>Status</th><th>Placed At</th>
          </tr>
        </thead>
        <tbody id="owner-orders-tbody"></tbody>
      </table>
    </section>
  </section>
</main>

<!-- Payment Modal -->
<div id="payment-modal" class="modal" role="dialog" aria-modal="true" aria-labelledby="payment-modal-title" aria-describedby="payment-modal-desc">
  <div class="modal-content">
    <button class="modal-close" aria-label="Close payment modal">&times;</button>
    <h3 id="payment-modal-title">Select Payment Method</h3>
    <div class="payment-methods">
      <button id="pay-card-btn">Pay with Card</button>
      <button id="pay-upi-btn">Pay with UPI</button>
    </div>
    <form id="card-payment-form" class="payment-form" aria-label="Card Payment Form">
      <label for="card-holder">Cardholder Name</label>
      <input type="text" id="card-holder" required autocomplete="off" />
      <label for="card-number">Card Number</label>
      <input type="text" id="card-number" maxlength="16" minlength="16" required autocomplete="off" pattern="\\d{16}" inputmode="numeric" />
      <label for="card-expiry">Expiry (MM/YY)</label>
      <input type="text" id="card-expiry" maxlength="5" placeholder="MM/YY" pattern="^(0[1-9]|1[0-2])\\/\\d{2}$" required autocomplete="off" />
      <label for="card-cvv">CVV</label>
      <input type="password" id="card-cvv" maxlength="3" minlength="3" required autocomplete="off" pattern="\\d{3}" inputmode="numeric" />
      <button type="submit" class="submit-payment" aria-label="Submit card payment">Pay ₹<span id="payment-amount-card">0.00</span></button>
    </form>
    <form id="upi-payment-form" class="payment-form" aria-label="UPI Payment Form">
      <label for="upi-id">UPI ID</label>
      <input type="text" id="upi-id" placeholder="example@bank" required autocomplete="off" />
      <button type="submit" class="submit-payment" aria-label="Submit UPI payment">Pay ₹<span id="payment-amount-upi">0.00</span></button>
    </form>
    <div id="payment-success-message" class="payment-success" role="alert" aria-live="assertive" style="display:none;">
      Payment Successful! Thank you for your purchase.
    </div>
  </div>
</div>

<script>
  (() => {
    // Data models
    const STORAGE_KEYS = {
      products: 'retailShop_products',
      orders: 'retailShop_orders'
    };

    // Elements
    const btnCustomer = document.getElementById('btn-customer');
    const btnOwner = document.getElementById('btn-owner');
    const customerView = document.getElementById('customer-view');
    const ownerView = document.getElementById('owner-view');
    const productsList = document.getElementById('products-list');
    const searchInput = document.getElementById('search-input');
    const searchClear = document.getElementById('search-clear');
    const cartItemsUl = document.getElementById('cart-items');
    const cartTotalEl = document.getElementById('cart-total');
    const checkoutBtn = document.getElementById('checkout-btn');
    const paymentModal = document.getElementById('payment-modal');
    const modalCloseBtn = paymentModal.querySelector('.modal-close');
    const payCardBtn = document.getElementById('pay-card-btn');
    const payUpiBtn = document.getElementById('pay-upi-btn');
    const cardPaymentForm = document.getElementById('card-payment-form');
    const upiPaymentForm = document.getElementById('upi-payment-form');
    const paymentSuccessMessage = document.getElementById('payment-success-message');
    const paymentAmountCardSpan = document.getElementById('payment-amount-card');
    const paymentAmountUpiSpan = document.getElementById('payment-amount-upi');

    // Owner Elements
    const productForm = document.getElementById('product-form');
    const productIdInput = document.getElementById('product-id');
    const productNameInput = document.getElementById('product-name');
    const productDescInput = document.getElementById('product-description');
    const productPriceInput = document.getElementById('product-price');
    const productImageInput = document.getElementById('product-image');
    const productSubmitBtn = document.getElementById('product-submit-btn');
    const ownerProductsTbody = document.getElementById('owner-products-tbody');
    const ownerOrdersTbody = document.getElementById('owner-orders-tbody');

    // State
    let products = [];
    let cart = {};
    let orders = [];

    // Util - load from localStorage
    function loadData() {
      const productsJson = localStorage.getItem(STORAGE_KEYS.products);
      const ordersJson = localStorage.getItem(STORAGE_KEYS.orders);
      products = productsJson ? JSON.parse(productsJson) : [];
      orders = ordersJson ? JSON.parse(ordersJson) : [];
    }
    // Util - save to localStorage
    function saveData() {
      localStorage.setItem(STORAGE_KEYS.products, JSON.stringify(products));
      localStorage.setItem(STORAGE_KEYS.orders, JSON.stringify(orders));
    }

    // Utility: generate unique ID
    function generateId() {
      return 'id-' + Math.random().toString(36).substr(2, 9);
    }

    // Switch view: customer or owner
    function switchView(view) {
      if(view === 'customer') {
        customerView.style.display = 'block';
        ownerView.style.display = 'none';
        btnCustomer.classList.add('active');
        btnOwner.classList.remove('active');
      } else {
        customerView.style.display = 'none';
        ownerView.style.display = 'block';
        btnCustomer.classList.remove('active');
        btnOwner.classList.add('active');
      }
      resetSearch();
      renderProducts();
      renderOwnerProducts();
      renderOrders();
      resetForm();
      resetCartView();
    }

    // Render products on customer view filtered by search
    function renderProducts() {
      const query = searchInput.value.trim().toLowerCase();
      const filteredProducts = products.filter(p => 
        p.name.toLowerCase().includes(query) || p.description.toLowerCase().includes(query)
      );
      productsList.innerHTML = '';
      if(filteredProducts.length === 0){
        productsList.innerHTML = '<p>No products found.</p>';
        return;
      }
      filteredProducts.forEach(p => {
        const card = document.createElement('article');
        card.className = 'product-card';
        card.setAttribute('tabindex', '0');
        card.innerHTML = `
          <img src="${p.image || 'https://via.placeholder.com/250x150?text=No+Image'}" alt="${p.name}" class="product-image" />
          <div class="product-name">${p.name}</div>
          <div class="product-description">${p.description}</div>
          <div class="product-price">₹${Number(p.price).toFixed(2)}</div>
          <button class="add-to-cart-btn" aria-label="Add ${p.name} to cart">Add to Cart</button>
        `;
        const btnAdd = card.querySelector('.add-to-cart-btn');
        btnAdd.addEventListener('click', () => {
          addToCart(p.id);
        });
        productsList.appendChild(card);
      });
    }

    // Add product to cart
    function addToCart(productId) {
      cart[productId] = (cart[productId] || 0) + 1;
      updateCartView();
    }

    // Update cart view
    function updateCartView() {
      cartItemsUl.innerHTML = '';
      const productIds = Object.keys(cart);
      if(productIds.length === 0){
        cartItemsUl.innerHTML = '<li>Your cart is empty.</li>';
        checkoutBtn.disabled = true;
        cartTotalEl.textContent = 'Total: ₹0.00';
        return;
      }
      let total = 0;
      productIds.forEach(pid => {
        const product = products.find(p => p.id === pid);
        if(!product) return;
        const qty = cart[pid];
        const li = document.createElement('li');
        li.innerHTML = `
          <span class="cart-item-name">${product.name}</span>
          <span>
            <button class="cart-item-dec" aria-label="Decrease quantity for ${product.name}">-</button>
            <span class="cart-item-qty" aria-live="polite">${qty}</span>
            <button class="cart-item-inc" aria-label="Increase quantity for ${product.name}">+</button>
            <button class="cart-item-remove" title="Remove ${product.name} from cart" aria-label="Remove from cart">&times;</button>
          </span>
        `;
        const decBtn = li.querySelector('.cart-item-dec');
        const incBtn = li.querySelector('.cart-item-inc');
        const removeBtn = li.querySelector('.cart-item-remove');
        decBtn.addEventListener('click', () => {
          if(cart[pid] > 1){
            cart[pid]--;
          } else {
            delete cart[pid];
          }
          updateCartView();
        });
        incBtn.addEventListener('click', () => {
          cart[pid]++;
          updateCartView();
        });
        removeBtn.addEventListener('click', () => {
          delete cart[pid];
          updateCartView();
        });
        cartItemsUl.appendChild(li);
        total += qty * Number(product.price);
      });
      cartTotalEl.textContent = 'Total: ₹' + total.toFixed(2);
      checkoutBtn.disabled = total === 0;
    }

    // Reset cart view completely
    function resetCartView() {
      cart = {};
      updateCartView();
    }

    // Reset search input and results
    function resetSearch() {
      searchInput.value = '';
    }

    // Owner: render products in table for management
    function renderOwnerProducts() {
      ownerProductsTbody.innerHTML = '';
      if(products.length === 0){
        ownerProductsTbody.innerHTML = '<tr><td colspan="4" style="text-align:center;padding:1rem;color:#777;">No products available.</td></tr>';
        return;
      }
      products.forEach(p => {
        const tr = document.createElement('tr');
        tr.innerHTML = `
          <td>${p.name}</td>
          <td>₹${Number(p.price).toFixed(2)}</td>
          <td>${p.description}</td>
          <td>
            <button class="btn-edit" aria-label="Edit product ${p.name}">Edit</button>
            <button class="btn-delete" aria-label="Delete product ${p.name}">Delete</button>
          </td>
        `;
        const btnEdit = tr.querySelector('.btn-edit');
        const btnDelete = tr.querySelector('.btn-delete');
        btnEdit.addEventListener('click', () => {
          loadProductIntoForm(p.id);
        });
        btnDelete.addEventListener('click', () => {
          if(confirm(`Are you sure you want to delete product "${p.name}"?`)){
            products = products.filter(prod => prod.id !== p.id);
            saveData();
            renderOwnerProducts();
            renderProducts();
          }
        });
        ownerProductsTbody.appendChild(tr);
      });
    }

    // Load a product's data into the owner form for editing
    function loadProductIntoForm(id) {
      const p = products.find(prod => prod.id === id);
      if(!p) return;
      productIdInput.value = p.id;
      productNameInput.value = p.name;
      productDescInput.value = p.description;
      productPriceInput.value = p.price;
      productImageInput.value = p.image || '';
      productSubmitBtn.textContent = "Update Product";
      productNameInput.focus();
    }

    // Clear and reset owner product form
    function resetForm() {
      productIdInput.value = '';
      productNameInput.value = '';
      productDescInput.value = '';
      productPriceInput.value = '';
      productImageInput.value = '';
      productSubmitBtn.textContent = "Add Product";
    }

    // Owner: render orders in table
    function renderOrders() {
      ownerOrdersTbody.innerHTML = '';
      if(orders.length === 0){
        ownerOrdersTbody.innerHTML = '<tr><td colspan="5" style="text-align:center;padding:1rem;color:#777;">No orders placed yet.</td></tr>';
        return;
      }
      orders.forEach(order => {
        const tr = document.createElement('tr');
        const itemsSummary = order.items.map(i => {
          const p = products.find(prod => prod.id === i.productId);
          if(!p) return '';
          return `${p.name} (x${i.qty})`;
        }).join(', ');
        tr.innerHTML = `
          <td>${order.id}</td>
          <td>${itemsSummary}</td>
          <td>₹${order.total.toFixed(2)}</td>
          <td class="order-status">${order.status}</td>
          <td>${new Date(order.placedAt).toLocaleString()}</td>
        `;
        ownerOrdersTbody.appendChild(tr);
      });
    }

    // Event: submit product form (add or update product)
    productForm.addEventListener('submit', e => {
      e.preventDefault();
      const id = productIdInput.value;
      const name = productNameInput.value.trim();
      const description = productDescInput.value.trim();
      const price = parseFloat(productPriceInput.value);
      const image = productImageInput.value.trim();

      if(name === '' || description === '' || isNaN(price) || price < 0){
        alert('Please fill all fields with valid values.');
        return;
      }

      if(id) {
        // Update existing
        const index = products.findIndex(p => p.id === id);
        if(index >= 0) {
          products[index] = {id, name, description, price, image};
        }
      } else {
        // Add new product
        const newProd = {id: generateId(), name, description, price, image};
        products.push(newProd);
      }
      saveData();
      renderOwnerProducts();
      renderProducts();
      resetForm();
    });

    // Payment
    let paymentAmount = 0;
    let currentOrder = null;

    // Checkout button click
    checkoutBtn.addEventListener('click', () => {
      paymentAmount = calculateCartTotal();
      if(paymentAmount <= 0) return;
      openPaymentModal(paymentAmount);
    });

    function calculateCartTotal() {
      let total = 0;
      Object.entries(cart).forEach(([pid, qty]) => {
        const product = products.find(p => p.id === pid);
        if(product) {
          total += qty * Number(product.price);
        }
      });
      return total;
    }

    // Open payment modal
    function openPaymentModal(amount) {
      paymentSuccessMessage.style.display = 'none';
      cardPaymentForm.reset();
      upiPaymentForm.reset();
      cardPaymentForm.classList.remove('active');
      upiPaymentForm.classList.remove('active');
      paymentAmountCardSpan.textContent = amount.toFixed(2);
      paymentAmountUpiSpan.textContent = amount.toFixed(2);
      paymentModal.classList.add('active');
    }

    // Close payment modal
    modalCloseBtn.addEventListener('click', closePaymentModal);
    paymentModal.addEventListener('click', e => {
      if(e.target === paymentModal) {
        closePaymentModal();
      }
    });

    function closePaymentModal() {
      paymentModal.classList.remove('active');
    }

    // Payment method buttons
    payCardBtn.addEventListener('click', () => {
      cardPaymentForm.classList.add('active');
      upiPaymentForm.classList.remove('active');
    });
    payUpiBtn.addEventListener('click', () => {
      upiPaymentForm.classList.add('active');
      cardPaymentForm.classList.remove('active');
    });

    // Simulate order placement
    function placeOrder(paymentMethodData) {
      const orderId = generateId();
      const items = Object.entries(cart).map(([pid, qty]) => ({productId: pid, qty}));
      const total = calculateCartTotal();
      const order = {
        id: orderId,
        items,
        total,
        paymentMethod: paymentMethodData,
        status: 'Confirmed',
        placedAt: Date.now()
      };
      orders.push(order);
      saveData();
      renderOrders();
      resetCartView();
      closePaymentModal();
      paymentSuccessMessage.style.display = 'block';
      setTimeout(() => {
        paymentSuccessMessage.style.display = 'none';
      }, 4000);
    }

    // Handle card payment submission
    cardPaymentForm.addEventListener('submit', e => {
      e.preventDefault();
      // Validate inputs - HTML5 validation mostly
      if(!cardPaymentForm.checkValidity()) {
        cardPaymentForm.reportValidity();
        return;
      }
      // Simulate payment process delay
      cardPaymentForm.querySelector('.submit-payment').disabled = true;
      setTimeout(() => {
        placeOrder({
          method: 'Card',
          cardHolder: cardPaymentForm['card-holder'].value,
          cardNumber: '**** **** **** ' + cardPaymentForm['card-number'].value.slice(-4),
          amount: paymentAmount
        });
        cardPaymentForm.querySelector('.submit-payment').disabled = false;
      }, 1000);
    });

    // Handle UPI payment submission
    upiPaymentForm.addEventListener('submit', e => {
      e.preventDefault();
      if(!upiPaymentForm.checkValidity()) {
        upiPaymentForm.reportValidity();
        return;
      }
      upiPaymentForm.querySelector('.submit-payment').disabled = true;
      setTimeout(() => {
        placeOrder({
          method: 'UPI',
          upiId: upiPaymentForm['upi-id'].value,
          amount: paymentAmount
        });
        upiPaymentForm.querySelector('.submit-payment').disabled = false;
      }, 1000);
    });

    // Search input events
    searchInput.addEventListener('input', () => {
      renderProducts();
    });
    searchClear.addEventListener('click', () => {
      searchInput.value = '';
      renderProducts();
      searchInput.focus();
    });

    // Button click view toggle
    btnCustomer.addEventListener('click', () => switchView('customer'));
    btnOwner.addEventListener('click', () => switchView('owner'));

    // Initial load
    loadData();

    // If no products, add general store product list
    if(products.length === 0) {
      products = [
        {
          id: generateId(),
          name: 'Rice (5 kg)',
          description: 'Premium Basmati rice, ideal for all your cooking needs.',
          price: 350.00,
          image: 'https://images.unsplash.com/photo-1516685304081-de7947d419d3?auto=format&fit=crop&w=400&q=80'
        },
        {
          id: generateId(),
          name: 'Wheat Flour (Atta) (5 kg)',
          description: 'Fresh whole wheat flour for making rotis and other breads.',
          price: 180.00,
          image: 'https://images.unsplash.com/photo-1613936087686-3f32ffccf63e?auto=format&fit=crop&w=400&q=80'
        },
        {
          id: generateId(),
          name: 'Sugar (1 kg)',
          description: 'Refined white sugar, perfect for baking and sweetening.',
          price: 45.00,
          image: 'https://images.unsplash.com/photo-1573496771133-cb909afdb58c?auto=format&fit=crop&w=400&q=80'
        },
        {
          id: generateId(),
          name: 'Salt (1 kg)',
          description: 'Pure rock salt, essential for daily cooking.',
          price: 20.00,
          image: 'https://images.unsplash.com/photo-1605254905645-2c44dd805a7c?auto=format&fit=crop&w=400&q=80'
        },
        {
          id: generateId(),
          name: 'Tea Powder (100 gm)',
          description: 'Strong and refreshing tea powder for daily tea lovers.',
          price: 60.00,
          image: 'https://images.unsplash.com/photo-1513185918532-2810e8bd588f?auto=format&fit=crop&w=400&q=80'
        },
        {
          id: generateId(),
          name: 'Mustard Oil (1 L)',
          description: 'Pure mustard oil, rich aroma and healthy cooking oil.',
          price: 150.00,
          image: 'https://images.unsplash.com/photo-1600185360866-0ee6784e0d3b?auto=format&fit=crop&w=400&q=80'
        },
        {
          id: generateId(),
          name: 'Soap Bar (Pack of 3)',
          description: 'Gentle cleansing soap with moisturizing properties.',
          price: 90.00,
          image: 'https://images.unsplash.com/photo-1507525428034-b723cf961d3e?auto=format&fit=crop&w=400&q=80'
        },
        {
          id: generateId(),
          name: 'Toothpaste (100 gm)',
          description: 'Effective cavity protection toothpaste with fresh mint flavor.',
          price: 40.00,
          image: 'https://images.unsplash.com/photo-1509475826633-fed577a2c71b?auto=format&fit=crop&w=400&q=80'
        },
        {
          id: generateId(),
          name: 'Pen (Pack of 5)',
          description: 'Smooth writing blue ink ballpoint pens perfect for daily use.',
          price: 70.00,
          image: 'https://images.unsplash.com/photo-1524995997946-a1c2e315a42f?auto=format&fit=crop&w=400&q=80'
        },
        {
          id: generateId(),
          name: 'Notebook (200 pages)',
          description: 'Durable notebook ideal for school and office work.',
          price: 120.00,
          image: 'https://images.unsplash.com/photo-1544716278-ca5e3f4abd8c?auto=format&fit=crop&w=400&q=80'
        },
        {
          id: generateId(),
          name: 'Biscuits (Pack of 2)',
          description: 'Crunchy and tasty biscuits, great for tea time snacks.',
          price: 50.00,
          image: 'https://images.unsplash.com/photo-1525755662778-989d0524087e?auto=format&fit=crop&w=400&q=80'
        },
        {
          id: generateId(),
          name: 'Chips (Pack of 1)',
          description: 'Salted potato chips, crispy and delicious.',
          price: 30.00,
          image: 'https://images.unsplash.com/photo-1541602178243-3ef0216a5cae?auto=format&fit=crop&w=400&q=80'
        },
        {
          id: generateId(),
          name: 'Cooking Gas Cylinder (14.2 kg)',
          description: 'Standard LPG gas cylinder for household cooking needs.',
          price: 900.00,
          image: 'https://images.unsplash.com/photo-1556742400-b5c0862d5f81?auto=format&fit=crop&w=400&q=80'
        },
        {
          id: generateId(),
          name: 'Detergent Powder (1 kg)',
          description: 'Effective detergent powder for laundry and cleaning.',
          price: 110.00,
          image: 'https://images.unsplash.com/photo-1571171637578-41bc2dd41cd2?auto=format&fit=crop&w=400&q=80'
        },
        {
          id: generateId(),
          name: 'Toilet Cleaner (500 ml)',
          description: 'Powerful toilet cleaner to keep your bathroom sparkling clean.',
          price: 85.00,
          image: 'https://images.unsplash.com/photo-1571242883449-dd3c3de7be3d?auto=format&fit=crop&w=400&q=80'
        }
      ];
      saveData();
    }

    switchView('customer');
  })();
</script>
</body>
</html>

