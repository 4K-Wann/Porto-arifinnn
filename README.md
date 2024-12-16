<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio Arifin</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f4f4f9;
        }

        header {
            text-align: center;
            padding: 2rem 0 4rem 0;
            background: rgb(2,0,36);
            background: linear-gradient(90deg, rgba(2,0,36,1) 0%, rgba(9,9,121,1) 35%, rgba(0,212,255,1) 100%);
            color: #fff;
            position: relative;
        }

        .profile-image {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 1rem;
        }

        header h1 {
            font-size: 2.5rem;
            animation: fadeInDown 1.5s ease;
        }

        header p {
            margin-top: 1rem;
            font-size: 1.2rem;
        }

        .wave-header {
            position: absolute;
            bottom: 0;
            left: 0;
            width: 100%;
            height: 100px;
        }

        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            margin-top: 1rem;
        }

        nav ul li {
            margin: 0 1rem;
        }

        nav ul li a {
            text-decoration: none;
            color: #fff;
            font-weight: bold;
        }

        nav ul li a:hover {
            color: #f4a261;
        }

        .about {
            text-align: center;
            padding: 3rem 1rem;
        }

        .about h2 {
            font-size: 2rem;
            margin-bottom: 1rem;
        }

        .about p {
            max-width: 600px;
            margin: 0 auto;
            font-size: 1rem;
        }

        .projects {
            background: rgb(2,0,36);
            background: linear-gradient(90deg, rgba(2,0,36,1) 0%, rgba(9,9,121,1) 35%, rgba(0,212,255,1) 100%);
            color: #444;
            padding: 3rem 1rem;
            position: relative;
        }

        .wave-projects {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100px;
        }

        .projects h2 {
            color: #fff;
            text-align: center;
            font-size: 2rem;
            margin-bottom: 1rem;
        }

        .project-grid {
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .project-item {
            width: 100%;
            max-width: 600px;
            background-color: white;
            padding: 80px 70px;
            border-radius: 8px;
            text-align: center;
            transition: transform 0.3s ease;
        }

        .project-item:hover {
            transform: translateY(-10px);
        }

        .project-item h3 {
            margin-bottom: 1rem;
        }

        .project-item a{
            padding: 10px 5px;
            background-color: #20c997;
            text-decoration: none;
            color: #fff;
            border-radius: 10px;
        }

        .project-item a:hover{
            padding: 10px 5px;
            background-color: #20c911;
            text-decoration: none;
            color: #fff;
            border-radius: 10px;
        }



        footer {
            text-align: center;
            padding: 1rem 0;
            background-color: #fff;
            color: #444;
        }

        @keyframes fadeInDown {
            0% {
                opacity: 0;
                transform: translateY(-20px);
            }
            100% {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>

<header>
    <img src="WhatsApp Image 2024-12-16 at 21.15.12_5e852652.jpg" alt="Foto Profil" class="profile-image">
    <h1>Selamat Datang di Portofolio Saya</h1>
    <p>Halo, saya Arifin - Mahasiswa Universitas Negeri Medan</p>
</header>

<section class="about" id="about">
    <h2>Tentang Saya</h2>
    <p>Saya seorang pengembang web yang bersemangat menciptakan aplikasi dan situs web yang menarik, cepat, dan ramah pengguna. Dengan keahlian di bidang front-end.</p>
</section>

<section class="projects" id="projects">
    <h2>Proyek</h2>
    <div class="project-grid">
        <div class="project-item">
            <h3>Proyek UMKM Jaya</h3>
            <img src="Screenshot 2024-12-17 003000.png" alt="imageUMKM" width="100%">
            <p>Website "UKM Jaya" dikembangkan untuk menjawab kebutuhan mahasiswa dalam 
                mengakses informasi Unit Kegiatan Mahasiswa (UKM) secara lebih cepat dan efisien.</p>
                <br>
                <a href="https://ukm-manajemen.vercel.app/">Klik untuk melihat</a>
        </div>
    </div>
</section>

<footer>
    <p>&copy; 2024 Arifin. Semua Hak Dilindungi.</p>
</footer>

</body>
</html>
