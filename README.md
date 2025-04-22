<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Saya</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&family=Roboto:wght@300;400;500&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #007bff8f; /* Warna biru */
            background-image: linear-gradient(135deg, rgba(255, 255, 255, 0.315) 25%, transparent 25%, transparent 75%, rgba(255, 255, 255, 0.39) 75%, rgba(255, 255, 255, 0.1)), linear-gradient(225deg, rgba(255, 255, 255, 0.1) 25%, transparent 25%, transparent 75%, rgba(255, 255, 255, 0.1) 75%, rgba(255, 255, 255, 0.1));
            background-size:80px 80px; /* Ukuran garis */
            color: #333;
        }

        header {
            background: rgba(51, 51, 51, 0.8);
            color: #fff;
            padding: 30px; /* Menambah padding untuk memperlebar latar belakang */
            text-align: center;
        }

        nav ul {
            list-style: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }

        section {
            padding: 20px; /* Padding atas dan bawah */
            margin: 20px auto; /* Margin atas dan bawah */
            max-width: 800px; /* Membatasi lebar section */
            background: rgba(255, 255, 255, 0.9);
            border-radius: 10px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.2);
            padding-left: 50px; /* Menambah padding kiri */
            padding-right: 50px; /* Menambah padding kanan */
        }

        #profile-pic {
            width: 150px;
            border-radius: 50%;
            margin: 20px auto;
        }

        footer {
            text-align: center;
            padding: 30px; /* Menambah padding untuk memperlebar latar belakang */
            background: rgba(51, 51, 51, 0.582);
            color: #fff;
        }

        h2 {
            font-family: 'Roboto', sans-serif; /* Menggunakan Roboto untuk judul */
        }

        h3 {
            font-weight: bold; /* Menebalkan subjudul */
        }
    </style>
</head>
<body>
    <header>
        <h1>JAUZAA HANIIFAH</h1>
        <h1>2413025004</h1>
        <img id="profile-pic" src="file:///C:/Users/ASUS/Documents/portofolio/jauzaa.jpeg" alt="FOTO">
        <p>PENDIDIKAN TEKNOLOGI INFORMASI</p>
        <p>UNIVERSITAS LAMPUNG</p>
        <nav>
            <ul>
                <li><a href="#about">Tentang</a></li>
                <li><a href="#projects">Proyek</a></li>
                <li><a href="#contact">Kontak</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>Tentang Saya</h2>

        <h3>Domisili</h3>
        <p>Seputih Agung, Lampung Tengah.</p>

        <h3>Alumni</h3>
        <p>SMKN 1 Seputih Agung dari jurusan Teknik Komputer dan Jaringan.</p>

        <h3>Pendidikan Saat Ini</h3>
        <p>Saat ini saya adalah mahasiswa aktif di Universitas Lampung dari Fakultas Keguruan dan Ilmu Pendidikan,
           Jurusan Pendidikan Matematika dan Ilmu Pengetahuan Alam angkatan 2024 kelas B. Saya memiliki minat besar di bidang IT dan pendidikan serta berkomitmen untuk mengintegrasikan teknologi 
           dalam proses pembelajaran guna menciptakan pengalaman belajar yang lebih efektif dan interaktif bagi siswa.</p>
    </section>

    <section id="projects">
        <h2>Proyek Saya</h2>
        <ul>
            <li>
                <h3>Proyek 1</h3>
                <p>Deskripsi singkat tentang proyek ini.</p>
                <a href="https://github.com/username/proyek1">Lihat di GitHub</a>
            </li>
            <li>
                <h3>Proyek 2</h3>
                <p>Deskripsi singkat tentang proyek ini.</p>
                <a href="https://github.com/username/proyek2">Lihat di GitHub</a>
            </li>
            <!-- Tambahkan lebih banyak proyek sesuai kebutuhan -->
        </ul>
    </section>

    <section id="contact">
        <h2>Kontak</h2>
        <p>Email: <a href="mailto:jauzaahaniifah@gmail.com">jauzaahaniifah@gmail.com</a></p>
        <p>Instagram: <a href="https://www.instagram.com/jzaahnfhh?igsh=dWFtbHdpbzZuNWJn">instagram</a></p>
    </section>

    <footer>
        <p>&copy; Tugas Grafika Komputer.</p>
    </footer>

    <script>
        console.log("Portfolio Saya");
    </script>
</body>
</html>
