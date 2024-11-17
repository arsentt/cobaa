<html>
<head>
    <title>Katalog UMKM Desa</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f0f2f5;
        }
        .header {
            text-align: center;
            padding: 30px;
            background: linear-gradient(135deg, #4CAF50, #45a049);
            color: white;
            border-radius: 10px;
            margin-bottom: 30px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
            padding: 20px 0;
        }
        .product-card {
            background: white;
            border-radius: 12px;
            padding: 20px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            transition: transform 0.2s;
        }
        .product-card:hover {
            transform: translateY(-5px);
        }
        .product-image {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 8px;
            margin-bottom: 15px;
        }
        .product-title {
            font-size: 20px;
            font-weight: bold;
            color: #2c3e50;
            margin: 10px 0;
        }
        .product-price {
            color: #4CAF50;
            font-size: 18px;
            font-weight: bold;
            margin: 10px 0;
        }
        .product-description {
            color: #666;
            margin: 15px 0;
            line-height: 1.5;
        }
        .contact-button {
            background: #4CAF50;
            color: white;
            padding: 12px 20px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            width: 100%;
            font-size: 16px;
            transition: background 0.2s;
        }
        .contact-button:hover {
            background: #45a049;
        }
        .category-tags {
            margin: 15px 0;
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
        }
        .tag {
            background: #e8f5e9;
            color: #4CAF50;
            padding: 6px 12px;
            border-radius: 20px;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Katalog UMKM Desa Sejahtera</h1>
        <p>Produk Lokal Berkualitas dari Tangan Kreatif Masyarakat</p>
    </div>

    <div class="product-grid">
        <!-- Produk 1 -->
        <div class="product-card">
            <img src="/api/placeholder/400/320" alt="Produk UMKM 1" class="product-image">
            <div class="product-title">Keripik Singkong "Kriuk Sejahtera"</div>
            <div class="category-tags">
                <span class="tag">Makanan Ringan</span>
                <span class="tag">Produk Lokal</span>
            </div>
            <div class="product-price">Rp 12.000 / 250gr</div>
            <div class="product-description">
                Keripik singkong renyah dengan berbagai varian rasa. 
                Terbuat dari singkong pilihan dan diolah secara higienis.
            </div>
            <button class="contact-button">Hubungi via WhatsApp</button>
        </div>

        <!-- Produk 2 -->
        <div class="product-card">
            <img src="/api/placeholder/400/320" alt="Produk UMKM 2" class="product-image">
            <div class="product-title">Tas Rajut "Kreasi Indah"</div>
            <div class="category-tags">
                <span class="tag">Kerajinan</span>
                <span class="tag">Fashion</span>
            </div>
            <div class="product-price">Rp 150.000</div>
            <div class="product-description">
                Tas rajut handmade dengan desain eksklusif. 
                Bahan berkualitas dan jahitan rapi.
            </div>
            <button class="contact-button">Hubungi via WhatsApp</button>
        </div>

        <!-- Produk 3 -->
        <div class="product-card">
            <img src="/api/placeholder/400/320" alt="Produk UMKM 3" class="product-image">
            <div class="product-title">Kopi Robusta "Aroma Desa"</div>
            <div class="category-tags">
                <span class="tag">Minuman</span>
                <span class="tag">Produk Premium</span>
            </div>
            <div class="product-price">Rp 45.000 / 250gr</div>
            <div class="product-description">
                Kopi robusta premium hasil petani lokal. 
                Diolah dengan metode modern untuk rasa terbaik.
            </div>
            <button class="contact-button">Hubungi via WhatsApp</button>
        </div>
    </div>
</body>
</html>
