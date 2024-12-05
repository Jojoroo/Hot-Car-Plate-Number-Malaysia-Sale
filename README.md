<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hot Plates Malaysia</title>
    <style>
        /* General Styling */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        header {
            background-color: #f8b400;
            color: white;
            text-align: center;
            padding: 20px 10px;
        }
        header h1 {
            margin: 0;
        }
        header p {
            margin: 5px 0 0;
        }
        .search-section {
            padding: 20px;
            text-align: center;
        }
        .search-section input {
            padding: 10px;
            width: 60%;
            max-width: 400px;
            margin-bottom: 10px;
        }
        .search-section button {
            padding: 10px 20px;
            background-color: #f8b400;
            color: white;
            border: none;
            cursor: pointer;
            margin: 5px;
            border-radius: 5px;
        }
        .search-section button:hover {
            background-color: #d18f00;
        }
        .product-section {
            padding: 20px;
            text-align: center;
        }
        .product-section h2 {
            margin-bottom: 20px;
        }
        .product-grid {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .product {
            border: 1px solid #ddd;
            padding: 15px;
            width: 220px;
            text-align: center;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            background-color: white;
        }
        .product img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }
        .product h3 {
            margin: 10px 0;
            font-size: 1.2em;
        }
        .product p {
            margin: 5px 0;
            font-size: 1em;
            color: #555;
        }
        .product a {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 15px;
            background-color: #25d366;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }
        .product a:hover {
            background-color: #1eae5d;
        }
	.seller-button {
    		display: inline-block;
    		padding: 15px 40px;
   		 font-size: 20px;
   		 font-weight: bold;
   		 color: white;
   		 background: linear-gradient(45deg, #ff5722, #ff9800); /* Gradient effect */
   		 border: none;
   		 border-radius: 30px;
   		 text-decoration: none;
   		 cursor: pointer;
   		 box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
   		 transition: transform 0.2s, box-shadow 0.2s, background 0.2s;
	}

	.seller-button:hover {
   		 transform: translateY(-3px); /* Hover lift effect */
   		 box-shadow: 0 6px 12px rgba(0, 0, 0, 0.3);
   		 background: linear-gradient(45deg, #ff9800, #ff5722); /* Reverse gradient */
	}

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }
        footer a {
            color: #f8b400;
            text-decoration: none;
        }
    </style>
	<!-- Google Analytics -->
		<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR_TRACKING_ID"></script>
		<script>
 		 window.dataLayer = window.dataLayer || [];
  		function gtag(){dataLayer.push(arguments);}
  		gtag('js', new Date());
  		gtag('config', 'YOUR_TRACKING_ID');
	</script>

</head>
<body>

<header>
    <h1>Hot Plates Malaysia</h1>
    <p>Find Your Dream Car Number Plate Today!</p>
</header>

<div class="search-section">
    <h2>Search for Your Desired Plate Number</h2>
    <div>
        <input id="searchInput" type="text" placeholder="Enter alphabet or number">
    </div>
    <div class="search-buttons">
    <button onclick="searchByAlphabet()">Search with Alphabet</button>
    <button onclick="searchByNumber()">Search with Number</button>
</div>
<div class="reset-section">
    <button onclick="resetFilter()" class="reset-button">Back to All Listings</button>
</div>
</div>

<div class="product-section">
    <h2>Popular Plates for Sale</h2>
    <div class="product-grid">
        <!-- Product 1 -->
        <div class="product">
            <img src="https://via.placeholder.com/200x100/000000/FFFFFF?text=ABC1234" alt="ABC1234">
            <h3>ABC1234</h3>
            <p>Price: RM 5,000</p>
		<p>State: Johor</p>
            <a href="https://wa.me/60123456789?text=Hi,%20I%20am%20interested%20in%20the%20plate%20number%20ABC1234.">Contact Seller</a>
        </div>
        <!-- Product 2 -->
        <div class="product">
            <img src="https://via.placeholder.com/200x100/000000/FFFFFF?text=XYZ9999" alt="XYZ9999">
            <h3>XYZ9999</h3>
            <p>Price: RM 8,000</p>
	<p>State: Johor</p>
            <a href="https://wa.me/60123456789?text=Hi,%20I%20am%20interested%20in%20the%20plate%20number%20XYZ9999.">Contact Seller</a>
        </div>
        <!-- Product 3 -->
        <div class="product">
            <img src="https://via.placeholder.com/200x100/000000/FFFFFF?text=JHJ1010" alt="JHJ1010">
            <h3>JHJ1010</h3>
            <p>Price: RM 10,000</p>
		<p>State: Johor</p>
            <a href="https://wa.me/60123456789?text=Hi,%20I%20am%20interested%20in%20the%20plate%20number%20JHJ1010.">Contact Seller</a>
	</div>
	<!-- Product 4 -->
        <div class="product">
            <img src="https://via.placeholder.com/200x100/000000/FFFFFF?text=ABC1234" alt="ABC1234">
            <h3>ACC123</h3>
            <p>Price: RM 8,000</p>
		<p>State: Johor</p>
            <a href="https://wa.me/60123456789?text=Hi,%20I%20am%20interested%20in%20the%20plate%20number%20ABC1234.">Contact Seller</a>
        </div>
        <!-- Product 5 -->
        <div class="product">
            <img src="https://via.placeholder.com/200x100/000000/FFFFFF?text=XYZ9999" alt="XYZ9999">
            <h3>WWW9988</h3>
            <p>Price: RM 10,000</p>
		<p>State: Johor</p>
            <a href="https://wa.me/60123456789?text=Hi,%20I%20am%20interested%20in%20the%20plate%20number%20XYZ9999.">Contact Seller</a>
        </div>
        <!-- Product 6 -->
        <div class="product">
            <img src="https://via.placeholder.com/200x100/000000/FFFFFF?text=JHJ1010" alt="JHJ1010">
            <h3>JJJ7</h3>
            <p>Price: RM 20,000</p>
		<p>State: Johor</p>
            <a href="https://wa.me/60123456789?text=Hi,%20I%20am%20interested%20in%20the%20plate%20number%20JHJ1010.">Contact Seller</a>

        </div>
    </div>
</div>
<div class="seller-section">
    <h2>Do you have a Hot Car Number Plate to Sell?</h2>
    <p>Sign up now and let your plate reach thousands of potential buyers!</p>
    <a href="https://forms.gle/KyH15gn7aFdpp2ZG9" target="_blank" class="seller-button">Seller Sign Up</a>

</div>

<footer>
    <p>Contact us directly at <a href="https://wa.me/60123456789">+60123456789</a></p>
    <p>Email: <a href="mailto:info@hotplatesmalaysia.com">info@hotplatesmalaysia.com</a></p>
    <p>All plates listed are subject to availability. Prices include registration fees.</p>
</footer>

<script>
    function searchByAlphabet() {
        const query = document.getElementById("searchInput").value.toUpperCase();
        if (/^[a-zA-Z]+$/.test(query)) {
            filterProducts(query, true);
        } else {
            alert("Please enter alphabets only.");
        }
    }

    function searchByNumber() {
        const query = document.getElementById("searchInput").value;
        if (/^\d+$/.test(query)) {
            filterProducts(query, false);
        } else {
            alert("Please enter numbers only.");
        }
    }

    function filterProducts(query, isAlphabetSearch) {
        const products = document.querySelectorAll(".product");
        products.forEach(product => {
            const plateNumber = product.querySelector("h3").textContent.toUpperCase();
            const containsAlphabet = /[a-zA-Z]/.test(plateNumber);
            const containsNumber = /\d/.test(plateNumber);

            if (
                (isAlphabetSearch && containsAlphabet && plateNumber.includes(query)) ||
                (!isAlphabetSearch && containsNumber && plateNumber.includes(query))
            ) {
                product.style.display = "block";
            } else {
                product.style.display = "none";
            }
        });
    }

    function resetFilter() {
    const products = document.querySelectorAll(".product");
    products.forEach(product => {
        product.style.display = "block"; // Show all products
    });
    document.getElementById("searchInput").value = ""; // Clear the input field
}
</script>
</body>
</html>
