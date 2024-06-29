# Blueskyy
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Toko Online</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-image: url('https://pin.it/24laWnLje.jpg'); /* Ganti 'path/to/your/image.jpg' dengan path gambar Anda */
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            color: white; /* Warna font putih */
        }
        header {
            background-color: #ff6600;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        .container {
            max-width: 1000px;
            margin: 20px auto;
            padding: 20px;
            background-color: rgba(95, 158, 160, 0.8); /* Warna biru laut dengan transparansi */
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            color: white; /* Warna font putih */
        }
        .product {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .product-item {
            background-color: rgba(95, 158, 160, 0.8); /* Warna biru laut dengan transparansi */
            border: 1px solid #ddd;
            border-radius: 5px;
            margin: 10px;
            padding: 10px;
            width: 300px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            color: white; /* Warna font putih */
        }
        .product-item img {
            max-width: 100%;
            border-radius: 5px;
        }
        .product-item h3 {
            text-align: center;
            color: #ff6600;
        }
        .product-item p {
            text-align: center;
        }
        .contact {
            text-align: center;
            margin-top: 20px;
        }
        .contact a {
            color: #ff6600;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Toko Online</h1>
    </header>
    <div class="container">
        <div class="product">
            <div class="product-item">
                <img src="product1.jpg" alt="Produk 1">
                <h3>Produk 1</h3>
                <p>Rp 100.000</p>
                <p>Deskripsi singkat produk 1.</p>
            </div>
            <div class="product-item">
                <img src="product2.jpg" alt="Produk 2">
                <h3>Produk 2</h3>
                <p>Rp 150.000</p>
                <p>Deskripsi singkat produk 2.</p>
            </div>
            <div class="product-item">
                <img src="product3.jpg" alt="Produk 3">
                <h3>Produk 3</h3>
                <p>Rp 200.000</p>
                <p>Deskripsi singkat produk 3.</p>
            </div>
        </div>
        <div class="contact">
            <h2>Kontak Kami</h2>
            <p>Hubungi kami di <a href="mailto:contact@tokoonline.com">contact@tokoonline.com</a> atau <a href="https://wa.me/1234567890">WhatsApp</a></p>
        </div>
    </div>
</body>
</html>
