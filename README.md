#<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wolo Express - Dropshipping Rapide et Sécurisé</title>
    <style>
        /* Design général */
        body { font-family: 'Arial', sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; }
        
        /* En-tête (Header) */
        header { 
            background-color: #2c3e50; /* Bleu Nuit */
            color: white; 
            padding: 20px; 
            text-align: center; 
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        header h1 { margin: 0; font-size: 2.5em; text-transform: uppercase; letter-spacing: 2px; }
        header p { margin: 5px 0 0; color: #f39c12; font-weight: bold; } /* Orange Vif */

        /* Bannière */
        .hero { 
            background-color: #ecf0f1; 
            padding: 50px 20px; 
            text-align: center; 
            border-bottom: 5px solid #f39c12;
        }
        .hero h2 { color: #2c3e50; }
        .btn-main { 
            background-color: #f39c12; 
            color: white; 
            padding: 12px 25px; 
            text-decoration: none; 
            border-radius: 5px; 
            font-weight: bold;
            display: inline-block;
            transition: background-color 0.3s;
        }
        .btn-main:hover { background-color: #e67e22; }

        /* Grille de produits */
        .container { max-width: 1000px; margin: 30px auto; padding: 0 20px; }
        .products { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 25px; }
        
        /* Carte Produit */
        .product-card { 
            background: white; 
            border-radius: 8px; 
            overflow: hidden; 
            box-shadow: 0 4px 10px rgba(0,0,0,0.1); 
            transition: transform 0.3s;
        }
        .product-card:hover { transform: translateY(-5px); }
        .product-img { 
            width: 100%; 
            height: 220px; 
            background-color: #ddd; 
            display: flex; 
            align-items: center; 
            justify-content: center; 
            color: #555; 
            font-weight: bold;
            object-fit: cover; /* Assure que l'image couvre la zone */
        }
        .product-info { padding: 15px; text-align: center; }
        .price { color: #e74c3c; font-size: 1.4em; font-weight: bold; margin: 10px 0; }
        
        /* Style pour l'intégration PayPal */
        .paypal-integration { 
            margin-top: 15px; 
            padding-top: 15px; 
            border-top: 1px solid #eee;
        }

        /* Pied de page */
        footer { 
            background-color: #333; 
            color: white; 
            text-align: center; 
            padding: 25px; 
            margin-top: 50px; 
        }
    </style>
</head>
<body>

    <header>
        <h1>Wolo Express 🚀</h1>
        <p>Livraison Rapide • Paiement Sécurisé • Le meilleur du Dropshipping</p>
    </header>

    <div class="hero">
        <h2>Découvrez nos produits incontournables</h2>
        <p>Profitez de notre sélection d'articles tendances avec le meilleur rapport qualité/prix.</p>
        <br>
        <a href="#shop" class="btn-main">Commencer le shopping</a>
    </div>

    <div class="container" id="shop">
        <h3 style="text-align:center; color:#2c3e50; margin-bottom: 30px;">Nos Produits du Moment</h3>
        <div class="products">
            
            <div class="product-card">
                <img src="https://via.placeholder.com/600x400?text=IMAGE+PRODUIT+1" alt="Produit 1" class="product-img">
                
                <div class="product-info">
                    <h4>Montre Sport Tactile</h4>
                    <p class="price">29.99 €</p>
                    
                    <div class="paypal-integration">
                        <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
                            <input type="hidden" name="cmd" value="_s-xclick">
                            <input type="hidden" name="hosted_button_id" value="VOTRECODEUNIQUE1"> 
                            <input type="image" src="https://www.paypalobjects.com/fr_FR/FR/i/btn/btn_buynow_LG.gif" border="0" name="submit" alt="Payer maintenant avec PayPal">
                        </form>
                        <small style="color:#888;">Paiement sécurisé via PayPal.</small>
                    </div>
                </div>
            </div>

            <div class="product-card">
                <img src="https://via.placeholder.com/600x400?text=IMAGE+PRODUIT+2" alt="Produit 2" class="product-img">
                
                <div class="product-info">
                    <h4>Mini Écouteurs sans fil (Tendance)</h4>
                    <p class="price">19.99 €</p>
                    
                    <div class="paypal-integration">
                        <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
                            <input type="hidden" name="cmd" value="_s-xclick">
                            <input type="hidden" name="hosted_button_id" value="VOTRECODEUNIQUE2"> 
                            <input type="image" src="https://www.paypalobjects.com/fr_FR/FR/i/btn/btn_buynow_LG.gif" border="0" name="submit" alt="Payer maintenant avec PayPal">
                        </form>
                        </div>
                </div>
            </div>

            <div class="product-card">
                <img src="https://via.placeholder.com/600x400?text=IMAGE+PRODUIT+3" alt="Produit 3" class="product-img">
                
                <div class="product-info">
                    <h4>Lampe de Chevet Connectée</h4>
                    <p class="price">39.50 €</p>
                    
                    <div class="paypal-integration">
                        <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
                            <input type="hidden" name="cmd" value="_s-xclick">
                            <input type="hidden" name="hosted_button_id" value="VOTRECODEUNIQUE3"> 
                            <input type="image" src="https://www.paypalobjects.com/fr_FR/FR/i/btn/btn_buynow_LG.gif" border="0" name="submit" alt="Payer maintenant avec PayPal">
                        </form>
                        </div>
                </div>
            </div>

        </div>
    </div>

    <footer>
        <p>&copy; 2024 Wolo Express. Tous droits réservés. Propulsé par le Dropshipping Manuel.</p>
    </footer>

</body>
</html>wolo-express-shop
