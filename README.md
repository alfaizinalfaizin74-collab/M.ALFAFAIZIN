
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV Digital - Nama Kamu</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }

        body {
            background: linear-gradient(135deg, #1e3c72, #2a5298);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }

        .container {
            background: #ffffff;
            max-width: 900px;
            width: 100%;
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 20px 40px rgba(0,0,0,0.2);
        }

        .header {
            background: linear-gradient(135deg, #667eea, #764ba2);
            color: white;
            text-align: center;
            padding: 40px 20px;
        }

        .header img {
            width: 140px;
            height: 140px;
            border-radius: 50%;
            object-fit: cover;
            border: 5px solid white;
            margin-bottom: 15px;
        }

        .header h1 {
            font-size: 28px;
            font-weight: 700;
        }

        .header p {
            font-size: 16px;
            opacity: 0.9;
        }

        .content {
            display: grid;
            grid-template-columns: 1fr 2fr;
        }

        .sidebar {
            background: #f4f6f9;
            padding: 30px;
        }

        .main {
            padding: 30px;
        }

        h2 {
            font-size: 18px;
            margin-bottom: 15px;
            color: #333;
            border-bottom: 2px solid #667eea;
            display: inline-block;
            padding-bottom: 5px;
        }

        ul {
            list-style: none;
            margin-bottom: 20px;
        }

        ul li {
            margin-bottom: 8px;
            font-size: 14px;
        }

        .job {
            margin-bottom: 20px;
        }

        .job h3 {
            font-size: 16px;
            font-weight: 600;
        }

        .job span {
            font-size: 13px;
            color: gray;
        }

        .job p {
            font-size: 14px;
            margin-top: 5px;
        }

        @media(max-width: 768px) {
            .content {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>

<div class="container">
    <div class="header">
        <img src="profile.jpg" alt="Foto Profil">
        <h1>Nama Kamu</h1>
        <p>Web Developer | UI Designer | Freelancer</p>
    </div>

    <div class="content">
        <div class="sidebar">
            <h2>Kontak</h2>
            <ul>
                <li>Email: alfaizinalfaizin74@gmail.com</li>
                <li>Phone: 0895424718827</li>
                <li>GitHub: github.com/alfaizin</li>
              
            </ul>

            <h2>Skills</h2>
            <ul>
                <li>HTML & CSS</li>
                <li>JavaScript</li>
                <li>React JS</li>
                <li>UI/UX Design</li>
            </ul>

            <h2>Pendidikan</h2>
            <ul>
                <li>JURUSAN Teknik Jaringan Komputer dan Telekomunikasi</li>
                <li>Lulusan SISWA SMKN 1 RANGKASBITUNG (2020-2024)</li>
            </ul>
        </div>

        <div class="main">
            <h2>Tentang Saya</h2>
            <p>
                Saya adalah seorang  SISWA SMKN 1 RANGKASBITUNG  SAYA developer yang berfokus pada pembuatan website modern,
                responsif, dan user-friendly. Berpengalaman dalam pengembangan frontend dan desain UI.
            </p>

            <br>

            <h2>Pengalaman PKL</h2>

            <div class="job">
                <h3>Frontend Developer</h3>
                <span>PT Contoh Indonesia | 2023 - Sekarang</span>
                <p>Mengembangkan dan maintenance website perusahaan menggunakan React dan Tailwind.</p>
            </div>

            <div class="job">
                <h3>Freelance Web Designer</h3>
                <span>2022 - 2023</span>
                <p>Membuat desain dan website untuk UMKM dan personal branding.</p>
            </div>

        </div>
    </div>
</div>

</body>
</html>

