<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shop Ayman - Gaming & High-Quality PC</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }

        header {
            background-color: #0d1117;
            padding: 20px;
            text-align: center;
            color: #fff;
        }

        header h1 {
            font-size: 2.5rem;
            margin: 0;
        }

        header p {
            margin: 10px 0;
            font-size: 1.2rem;
        }

        nav {
            background-color: #161b22;
            display: flex;
            justify-content: center;
            padding: 15px 0;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 20px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-size: 1.1rem;
            transition: color 0.3s ease;
        }

        nav ul li a:hover {
            color: #58a6ff;
        }

        .banner {
            background: url('images/gaming_banner.jpg') no-repeat center center/cover;
            height: 500px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
        }

        .banner h1 {
            font-size: 3rem;
            background-color: rgba(0, 0, 0, 0.5);
            padding: 10px 20px;
            border-radius: 10px;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }

        .product {
            background-color: #fff;
            border-radius: 15px;
            overflow: hidden;
            margin-bottom: 30px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            width: 31%;
            transition: transform 0.3s ease;
        }

        .product:hover {
            transform: scale(1.05);
        }

        .product img {
            width: 100%;
            border-bottom: 2px solid #58a6ff;
        }

        .product h3 {
            text-align: center;
            padding: 15px 0;
            background-color: #161b22;
            color: white;
            font-size: 1.3rem;
        }

        .product p {
            padding: 0 15px;
            font-size: 1.1rem;
            color: #444;
        }

        .product .price {
            padding: 0 15px;
            font-size: 1.4rem;
            color: #1f8b4c;
            font-weight: bold;
        }

        .product button {
            display: block;
            width: calc(100% - 30px);
            margin: 20px auto;
            padding: 10px 0;
            background-color: #1f8b4c;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 1.1rem;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .product button:hover {
            background-color: #14592e;
        }

        #contact {
            background-color: #161b22;
            color: white;
            padding: 40px 20px;
            text-align: center;
        }

        #contact h2 {
            font-size: 2rem;
            margin-bottom: 20px;
        }

        #contact p {
            font-size: 1.2rem;
            margin: 10px 0;
        }

        #contact a {
            color: #58a6ff;
            text-decoration: none;
        }

        footer {
            background-color: #0d1117;
            color: white;
            text-align: center;
            padding: 20px;
        }

        footer p {
            margin: 0;
        }

        @media (max-width: 768px) {
            .products {
                flex-direction: column;
                align-items: center;
            }

            .product {
                width: 80%;
            }

            .banner h1 {
                font-size: 2.2rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Shop Ayman - Gaming & High-Quality PCs</h1>
        <p>Votre destination pour les meilleurs PC Gaming</p>
    </header>

    <nav>
        <ul>
            <li><a href="#home">Accueil</a></li>
            <li><a href="#products">Produits</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section class="banner">
        <h1>Découvrez nos PC Gaming Haut de Gamme</h1>
    </section>

    <section id="products" class="container">
        <h2 style="text-align: center; margin-bottom: 40px;">Nos Produits</h2>
        <div class="products">
            <div class="product">
                <img src="https://nextlevelpc.ma/wp-content/uploads/2022/07/PC-GAMER-MAROC-AMD-RYZEN-5-RTX-2060-VENTUS-1024x1024.webp" alt="PC Gaming Professionnel">
                <h3>PC Gaming Professionnel</h3>
                <p>Le top de la performance pour les joueurs exigeants.</p>
                <p class="price">2500€</p>
                <button><a href="http://www.shopayman.ma" style="color: white; text-decoration: none;">Acheter Maintenant</a></button>
            </div>
            <div class="product">
                <img src="https://pcgamercasa.ma/10210-large_default/pc-gamer-casa-PROGTD.jpg" alt="PC Gaming Ultra">
                <h3>PC Gaming Ultra</h3>
                <p>Pour des graphismes fluides et des performances élevées.</p>
                <p class="price">2000€</p>
                <button><a href="http://www.shopayman.ma" style="color: black; text-decoration: none;">Acheter Maintenant</a></button>
                <section id="products" class="container">
    <h2 style="text-align: center; margin-bottom: 40px;">Nos Produits</h2>
    <div class="products">
        <div class="product">
            <img src="https://pcgamercasa.ma/10210-large_default/pc-gamer-casa-PROGTD.jpg" alt="PC Gaming Professionnel">
            <h3>PC Gaming Professionnel</h3>
            <p>Le top de la performance pour les joueurs exigeants.</p>
            <p class="price">2500€</p>
            <button><a href="http://www.shopayman.ma" style="color: white; text-decoration: none;" target="_blank">Acheter Maintenant</a></button>
        </div>
        <div class="product">
            <img src="https://www.ultrapc.ma/23765-large_default/pc-gamer-ultrapc-intel-core-i9-13900k-1tb-ssd-32gb-rtx4070ti.jpg" alt="PC Gaming Ultra">
            <h3>PC Gaming Ultra</h3>
            <p>Pour des graphismes fluides et des performances élevées.</p>
            <p class="price">2000€</p>
            <button><a href="http://www.shopayman.ma" style="color: white; text-decoration: none;" target="_blank">Acheter Maintenant</a></button>
        </div>
        <div class="product">
            <img src="https://www.ultrapc.ma/23765-large_default/pc-gamer-ultrapc-intel-core-i9-13900k-1tb-ssd-32gb-rtx4070ti.jpg" alt="Accessoires Gaming Pro">
            <h3>Accessoires Gaming Pro</h3>
            <p>Souris, claviers et casques de haute qualité.</p>
            <p class="price">À partir de 150€</p>
            <button><a href="http://www.shopayman.ma" style="color: white; text-decoration: none;" target="_blank">Acheter Maintenant</a></button>
        </div>
    </div>
</section>
                
