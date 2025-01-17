# nabila-uym
web
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio - NABILA</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        /* Reset dan Gaya Dasar */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Roboto', sans-serif;
            background: #f9f9f9;
            color: #333;
            line-height: 1.6;
        }

        /* Header */
        header {
            text-align: center;
            background: linear-gradient(135deg, #007bff, #0056b3);
            color: white;
            padding: 50px 20px;
        }
        header h1 {
            font-size: 3rem;
            margin-bottom: 10px;
        }
        header p {
            font-size: 1.2rem;
        }

        /* Main Section */
        main {
            padding: 20px;
            display: flex;
            flex-direction: column;
            gap: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }

        /* Card Layout */
        .card {
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            overflow: hidden;
        }
        .card-header {
            background: #007bff;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .card-content {
            padding: 20px;
        }
        .card img {
            width: 100%;
            display: block;
        }
        .card-content h3 {
            margin-bottom: 10px;
            color: #007bff;
        }

        /* About Me */
        .about-me {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            gap: 20px;
        }
        .about-me img {
            max-width: 150px;
            border-radius: 50%;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .about-me p {
            flex: 1;
            text-align: justify;
        }

        /* Footer */
        footer {
            text-align: center;
            background: #0056b3;
            color: white;
            padding: 10px;
            margin-top: 20px;
        }
        footer a {
            color: white;
            text-decoration: none;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Portofolio NABILA</h1>
        <p>Mahasiswa Universitas Yatsi Madani Prodi s1 Ilmu Komputer</p>
    </header>

    <!-- Main Section -->
    <main>
        <!-- About Me -->
        <section class="card">
            <div class="card-header">Tentang Saya</div>
            <div class="card-content about-me">
                <img src="Images profile.jpg.jpeg" alt="Foto Profil">
                <p>Halo! Saya NABILA sebagai seorang mahasiswa di Universitas Yatsi Madani,saya selalu berusaha untuk memberikan yang terbaik dalam setiap poyek yang saya kerjakan dan selalu antusias menghadapi tantangan baru. Saya memiliki kemampuan di bidang Microsoft Word dan Microsoft Excel, diluar kerjaan saya menikmati hobi saya mendengarkan musik dan mambantu pekerjaan rumah agar membuat saya tetap selalu produktif. </p>
            </div>
        </section>

        <!-- Projects -->
        <section class="card">
            <div class="card-header">Proyek Saya</div>
            <div class="card-content">
                <div style="display: flex; gap: 10px; flex-wrap: wrap;">
                    <div style="flex: 1 1 30%; text-align: center;">
                        <img src="Images project1.jpg.jpeg" alt="Project 1">
                        <h3>Proyek 1</h3>
                        <p>Moment penutupan pengajian yang dimana kebersamaan pengajian adalah momen indah untuk saling belajar,berbagi ilmu bersama teman-teman yang lain.</p>
                    </div>
                    <div style="flex: 1 1 30%; text-align: center;">
                        <img src="Images project2.jpg.jpeg" alt="Project 2">
                        <h3>Proyek 2</h3>
                        <p>Ini adalah kenangan indah saat kami mengadakan buka bersam.Ditengah kesibukan masing-masing,kami masih bisa berkumpul,berbagi cerita dan menikmati kebersamaan saat bulan suci ramadan dengan buka bersama.</p>
                    </div>
                    <div style="flex: 1 1 30%; text-align: center;">
                        <img src="Images project3.jpg.jpeg" alt="Project 3">
                        <h3>Proyek 3</h3>
                        <p>Ini adalah salah satu momen yang tidak akan saya lupakan. Dalam perjalanan ke sekolah saat hujan deras,kami semua berangkat bersama dengan penuh semangat. Meski basah dan dingin,tawa kami menghangatkan suasa. Perjalanan sederhana ini mengajarkan saya arti kebersamaan dan persahabatan sejati,yang selalu menjadi bagian daari diri saya hingga hari ini.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact -->
        <section class="card">
            <div class="card-header">Hubungi Saya</div>
            <div class="card-content">
                <p>Email: <a href="mailto:emailanda@example.com">admin@uym.ac.id</a></p>
                <p>Telepon: 081285286889</p>
                <p>Address: Jl.Aria Santika No.40A,RT.005/RW.011,Margasari,Kec.Karawaci,Kota Tangerang,Banten 15114.</p>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 <a href="#">Nabila</a>. Semua Hak Dilindungi.</p>
    </footer>

</body>
</html>
