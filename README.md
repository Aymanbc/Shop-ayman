
<body>
    <header>
        <h1 class="site-name">Ayman Shop 🇲🇦</h1>
        <h2>Bienvenue sur Shopfoot</h2>
        <p>Votre boutique de vêtements préférée pour les fans de football</p>
    </header>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ayman Shop - Boutique de T-Shirts 🇲🇦</title>
    <link rel="stylesheet" href="styles.css"> <!-- Lien vers le fichier CSS -->
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            
i8h            color: #fff;
            padding: 10px 20px;
            text-align: center;
        }
        .site-name {
            font-size: 12px;
            color: #fff;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .product {
            border: 1px solid #ddd;
            border-radius: 5px;
            margin: 10px;
            padding: 10px;
            text-align: center;
            transition: transform 0.2s;
            display: inline-block;
            width: 200px;
        }
        .product:hover {
            transform: scale(1.05);
        }
        .product img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }
        .footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: #fff;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        .info {
            background-color: #e7f3fe;
            border-left: 6px solid #2196F3;
            padding: 10px;
            margin: 20px 0;
            text-align: left;
        }
        .contact {
            margin-top: 20px;
            text-align: center;
        }
        .sort {
            margin-bottom: 20px;
            text-align: center;
        }
        .stars {
            color: #FFD700; /* Gold color for stars */
        }<!DOCTYPE html>
 lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ayman Shop - Boutique de T-Shirts 🇲🇦</title>
    <link rel="stylesheet" href="styles.css"> <!-- Lien vers le fichier CSS -->
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        /* Style de la barre de navigation */
        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background-color: #333;
            padding: 15px;
        }

        .navbar .menu {
            display: flex;
            gap: 20px;
        }

        .navbar .menu a {
            color: #fff;
            text-decoration: none;
            font-size: 16px;
            font-weight: bold;
            transition: color 0.3s;
        }

        .navbar .menu a:hover {
            color: #FFD700;
        }

        .navbar .icons {
            display: flex;
            align-items: center;
            gap: 20px;
        }

        .navbar .icons a {
            color: #fff;
            text-decoration: none;
            font-size: 20px;
            transition: transform 0.3s;
        }

        .navbar .icons a:hover {
            transform: scale(1.2);
        }

        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .product {
            border: 1px solid #ddd;
            border-radius: 5px;
            margin: 10px;
            padding: 10px;
            text-align: center;
            transition: transform 0.2s;
            display: inline-block;
            width: 200px;
        }

        .product:hover {
            transform: scale(1.05);
        }

        .product img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }

        .footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: #fff;
            position: relative;
            bottom: 0;
            width: 100%;
            text-align: center;
             display: inline-block;
        }

        .info {
            background-color: #e7f3fe;
            border-left: 6px solid #2196F3;
            padding: 10px;
            margin: 20px 0;
            text-align: left;
        }

        .contact {
            margin-top: 20px;
            text-align: center;
        }

        .btn {
            background-color: #FFD700;
            color: #333;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .btn:hover {
            background-color: #ffcc00;
        }

    </style>
</head>
<body>
    ----------------------------------*_*----------------------------------
    <!-- Boutons de navigation -->
        <button onclick="window.location.href='#collection';">Collection</button>
        <button onclick="window.location.href='#contact';">Contact</button>
        <button onclick="window.location.href='#top';">Accueil</button> <!-- Bouton Accueil -->
   

    <!-- Contenu principal -->
    <div class="container">
        <h2>Nos T-Shirts</h2>

        <div class="products">
            <!-- Produit FC Barcelone -->
            <div class="product" data-price="15">
                <img src="https://indiansoccermart.in/cdn/shop/products/Screenshot_2021_1116_162814_940x.jpg?v=1637060490" alt="T-Shirt FC Barcelone">
                <h3>FC Barcelone</h3>
                <p>Prix: 15,00 €</p>
                <div class="stars">★★★★☆</div>
                <button class="btn" onclick="window.location.href='barca.html';">Acheter</button>
            </div>

            <!-- Produit Real Madrid -->
            <div class="product" data-price="15">
                <img src="https://championgearz.co.za/cdn/shop/files/d65db9ad.jpg?v=1703359270&width=990" alt="T-Shirt Real Madrid">
                <h3>Real Madrid</h3>
                <p>Prix: 15,00 €</p>
                <div class="stars">★★★★☆</div>
                <button class="btn" onclick="window.location.href='real.html';">Acheter</button>
            </div>

            <!-- Produit Manchester United -->
            <div class="product" data-price="15">
                <img src="https://www.thejerseystreet.com/cdn/shop/products/manchester-united_retro-vintage-manchester-united-2007-2008-jersey-retro-vintage-manchester-united-2007-2008-1_900x.jpg?v=1623529311" alt="T-Shirt Manchester United">
                <h3>Manchester United</h3>
                <p>Prix: 15,00 €</p>
                <div class="stars">★★★★☆</div>
                <button class="btn" onclick="window.location.href='unated.html';">Acheter</button>
            </div>

            <!-- Produit Milan AC -->
            <div class="product" data-price="15">
                <img src="https://i0.wp.com/jaraguar.com/wp-content/uploads/2022/01/7414108f.jpg?resize=600%2C682&ssl=1" alt="T-Shirt Milan AC">
                <h3>Milan AC</h3>
                <p>Prix: 15,00 €</p>
                <div class="stars">★★★★☆</div>
                <button class="btn" onclick="window.location.href='milan.html';">Acheter</button>
            </div>

            <!-- Produit Juventus -->
            <div class="product" data-price="15">
                <img src="https://casualfootballshirts.co.uk/cdn/shop/files/CEB98AFA-1DFA-4B66-84CD-ACA8F3788F8C.jpg?v=1700748127&width=990" alt="T-Shirt Juventus">
                <h3>Juventus</h3>
                <p>Prix: 15,00 €</p>
                <div class="stars">★★★★☆</div>
                <button class="btn" onclick="window.location.href='juventus .html';">Acheter</button>
            </div>

            <!-- Produit AS FAR -->
            <div class="product" data-price="15">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTbMfWntD8G8R-vn0MOg-ukqODEEj3pepKp2w&s" alt="T-Shirt AS FAR">
                <h3>AS FAR</h3>
                <p>Prix: 15,00 €</p>
                <div class="stars">★★★★☆</div>
                <button class="btn" onclick="window.location.href='far.html';">Acheter</button>
            </div>

            <!-- Produit Arsenal -->
            <div class="product" data-price="15">
                <img src="https://www.thesoccerpark.com/cdn/shop/files/46fa691d_1080x.jpg?v=1686944270" alt="T-Shirt Arsenal">
                <h3>Arsenal</h3>
                <p>Prix: 15,00 €</p>
                <div class="stars">★★★★☆</div>
                <button class="btn" onclick="window.location.href='arsenal.html';">Acheter</button>
            </div>

            <!-- Produit Chelsea -->
            <div class="product" data-price="15">
                <img src="https://i.ebayimg.com/images/g/7CEAAOSwm-xjyzpW/s-l1200.webp" alt="T-Shirt Chelsea">
                <h3>Chelsea</h3>
                <p>Prix: 15,00 €</p>
                <div class="stars">★★★★☆</div>
                <button class="btn" onclick="window.location.href='chels.html';">Acheter</button>
            </div>
        </div>
          </div>
    </div>
</div>
  </div>
    </div>
</div>

<div id="collection" class="container">
    <h2>Nos Collections</h2>
    <div class="description">
        <p>•Découvrez notre collection exclusive de T-Shirt 100% coton.</p>     
        <p> •Livraison partout au Maroc🚚.</p>
        
    </div>
</div>

<footer id="contact">
    <div class="footer-content">
        <p>Contactez-nous : +212 684809473 | <a href="mailto:shopfoot@gmail.com">shopfoot@gmail.com</a></p>
        <p>&copy; 2024 Ayman Shop. Tous droits réservés.</p>
    </div>
</footer>


    <script>
        function sortProducts() {
            const select = document.getElementById('sort');
            const products = Array.from(document.querySelectorAll('.product'));
            const container = document.getElementById('product-list');

            products.sort((a, b) => {
                const priceA = parseFloat(a.getAttribute('data-price'));
                const priceB = parseFloat(b.getAttribute('data-price'));
                return select.value === 'asc' ? priceA - priceB : priceB - priceA;
            });

            container.innerHTML = '';
            products.forEach(product => container.appendChild(product));
        }
    </script>

</body>

