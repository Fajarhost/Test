DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nursatrias Si Artikel - Beranda</title>
    <link rel="stylesheet" href="css/style.css"> <!-- Ganti dengan lokasi CSS Anda -->
    <style>
        /* Gaya CSS tambahan untuk halaman */
        body {
            background-color: #f8f9fa;
            color: #333333;
            font-family: 'Montserrat', sans-serif; /* Ganti dengan font yang Anda inginkan */
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #007bff;
            color: #ffffff;
            padding: 20px 0;
            text-align: center;
            position: relative;
        }

        header h1 {
            margin: 0;
            font-size: 36px;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        nav {
            position: absolute;
            top: 20px;
            right: 20px;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }

        nav ul li {
            display: inline;
            margin-left: 20px;
        }

        nav ul li:first-child {
            margin-left: 0;
        }

        nav ul li a {
            color: #ffffff;
            text-decoration: none;
            font-size: 16px;
            transition: all 0.3s ease;
        }

        nav ul li a:hover {
            color: #f8f9fa;
        }

        /* Bagian atas halaman */
        #top-bar {
            background-color: #343a40;
            color: #ffffff;
            padding: 10px 0;
            text-align: center;
        }

        #top-bar p {
            margin: 0;
            font-size: 14px;
        }

        /* Bagian bawah halaman */
        footer {
            background-color: #007bff;
            color: #ffffff;
            text-align: center;
            padding: 20px 0;
        }

        footer p {
            margin: 0;
        }

        footer a {
            color: #ffffff;
            text-decoration: none;
            font-weight: bold;
        }

        footer a:hover {
            text-decoration: underline;
        }

        /* Gaya untuk judul dan subjudul */
        h1, h2 {
            font-family: 'Montserrat', sans-serif; /* Ganti dengan font yang Anda inginkan */
            color: #007bff;
            text-align: center;
        }

        h2 {
            margin-top: 0;
        }

        /* Gaya untuk konten utama */
        #main-content {
            max-width: 1200px;
            margin: 20px auto;
            padding: 0 20px;
        }

        #main-content p {
            line-height: 1.6;
        }

        /* Gaya untuk fitur-fitur */
        .feature {
            text-align: center;
            margin-bottom: 30px;
        }

        .feature img {
            width: 150px;
            border-radius: 50%;
            margin-bottom: 20px;
        }

        .feature h3 {
            font-size: 24px;
            margin-bottom: 10px;
        }

        .feature p {
            color: #555;
        }

        .feature a {
            color: #007bff;
            text-decoration: none;
            font-weight: bold;
        }

        .feature a:hover {
            text-decoration: underline;
        }
    </style>
</head>

<body>
    <!-- Header -->
    <header>
        <h1>Nursatrias Si Artikel</h1>
        <nav>
            <ul>
                <li><a href="index.html">Artikel</a></li>
                <li><a href="services.html">Layanan Kami</a></li>
                <li><a href="about.html">Tentang Kami</a></li>
                <li><a href="contact.html">Kontak</a></li>
                <li><a href="login.html">Masuk</a></li> <!-- Tambahkan tautan ke halaman masuk -->
                <li><a href="signup.html">Daftar</a></li> <!-- Tambahkan tautan ke halaman pendaftaran -->
            </ul>
        </nav>
    </header>

    <!-- Bagian atas halaman -->
    <section id="top-bar">
        <p>Selamat datang di Nursatrias Si Artikel. Temukan artikel-artikel berkualitas tinggi di sini!</p>
    </section>

    <!-- Konten utama -->
    <div id="main-content">
        <h2>Tentang Nursatrias Si Artikel</h2>
        <p>Nursatrias Si Artikel adalah platform online yang menyediakan akses ke berbagai artikel berkualitas tinggi dalam berbagai kategori. Kami bertujuan untuk memberikan informasi yang bermanfaat dan relevan bagi pembaca kami.</p>

        <h2>Fitur Unggulan</h2>
        <div class="feature">
            <img src="assets/images/feature1.jpg" alt="Fitur 1">
            <h3>Artikel Berkualitas Tinggi</h3>
            <p>Temukan berbagai artikel berkualitas tinggi di berbagai topik yang Anda minati.</p>
        </div>
        <div class="feature">
            <img src="assets/images/feature2.jpg" alt="Fitur 2">
            <h3>Pencarian Cepat</h3>
            <p>Manfaatkan fitur pencarian kami yang canggih untuk menemukan artikel dengan cepat dan mudah.</p>
        </div>
        <div class="feature">
            <img src="assets/images/feature3.jpg" alt="Fitur 3">
            <h3>Notifikasi Artikel Baru</h3>
            <p>Dapatkan pemberitahuan langsung ketika artikel baru dipublikasikan.</p>
        </div>
        <!-- Tambahkan lebih banyak fitur unggulan di sini -->
    </div>

    <!-- Footer -->
    <footer>
        <p>Hak Cipta &copy; 2024 NurSatria. | <a href="privacy.html">Kebijakan Privasi</a></p>
    </footer>
</body>

</html>
