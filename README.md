<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Ragam Pekalongan</title>
    <style>
            body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #0d97e7;
    color: white;
    padding: 20px 0;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

main {
    padding: 20px;
}

h2 {
    color: #0d97e7;
}

.tempat-item, .galeri-item {
    background: white;
    margin: 10px 0;
    padding: 15px;
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.galeri-item img {
    width: 400px;
    border-radius: 5px;
}

footer {
    background-color: #0d97e7;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: relative;
    bottom: 0;
    width: 100%;
}
    </style>
</head>
<body>
    <header>
        <h1>Ragam Pekalongan</h1>
        <nav>
            <ul>
                <li><a href="#tempat">Tempat Wisata</a></li>
                <li><a href="#galeri">Galeri</a></li>
                <li><a href="#kontak">Kontak</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="tempat">
            <h2>Tempat Wisata Religi</h2>
            <div class="tempat-item">
                <h3>Masjid Agung Pekalongan</h3>
                <p>Masjid Agung dengan arsitektur pilar-pilar kayu dan ornamen yang masih asli.</p>
            </div>
            <div class="tempat-item">
                <h3>Pura Kalinnga Satya Dharma </h3>
                <p>sebuah pura yang terletak di desa linggoasri,Kajen,Pekalongan,</div>
            </div>
        </section>
        <section id="galeri">
            <h2>Galeri</h2>
            <div class="galeri-item">
                <img src="masjid-agung.jpg" alt="Masjid Agung Pekalongan">
            </div>
            <div class="galeri-item">
                <img src="Pura Linggo.jpg" alt="Pura Kalingga Satya Dharma">
            </div>
        </section>
        <section id="kontak">
            <h2>Kontak Kami</h2>
            <p>Email: @ragam-pekalongan.com</p>
            <p>Telepon: 082324985383</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Ragam Pekalongan. All rights reserved.</p>
    </footer>
</body>
</html>
