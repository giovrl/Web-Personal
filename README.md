<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SMA N 9 Binsus Manado Keren</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      scroll-behavior: smooth;
    }

    /* Warna tema */
    :root {
      --hijau: #2ecc71;
      --hijau-tropis: #27ae60;
      --putih: #ffffff;
    }

    /* Navbar */
    .navbar {
      background-color: rgba(255, 255, 255, 0.95);
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }

    .navbar-brand {
      font-weight: 700;
      color: var(--hijau-tropis) !important;
    }

    .nav-link {
      color: #333 !important;
      font-weight: 500;
      transition: color 0.3s;
    }

    .nav-link:hover {
      color: var(--hijau-tropis) !important;
    }

    /* Hero section */
    .hero {
      background: url('https://i.ibb.co.com/GQ2j00zc/740d121e-59cc-41c8-85a3-2f4c148a9c24.jpg') center/cover no-repeat;
      height: 90vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: white;
      position: relative;
    }

    .hero::after {
      content: "";
      position: absolute;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background: rgba(0, 0, 0, 0.4);
    }

    .hero-content {
      position: relative;
      z-index: 1;
    }

    .hero h1 {
      font-size: 2.5rem;
      font-weight: 700;
    }

    .hero p {
      font-size: 1.2rem;
      margin-bottom: 1.5rem;
    }

    .btn-primary {
      background-color: var(--hijau-tropis);
      border: none;
    }

    .btn-primary:hover {
      background-color: var(--hijau);
    }

    /* Section umum */
    section {
      padding: 80px 0;
    }

    section h2 {
      text-align: center;
      font-weight: 700;
      margin-bottom: 50px;
      color: var(--hijau-tropis);
    }

    /* Card efek */
    .card {
      border: none;
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 20px rgba(0,0,0,0.15);
    }

    /* Galeri */
    .carousel-item img {
      height: 500px;
      object-fit: cover;
    }

    /* Footer */
    footer {
      background-color: var(--hijau-tropis);
      color: white;
      text-align: center;
      padding: 30px 10px;
    }

    footer a {
      color: white;
      text-decoration: none;
      margin: 0 8px;
    }

    /* Animasi fade-in */
    .fade-in {
      opacity: 0;
      transform: translateY(20px);
      transition: opacity 1s ease-out, transform 1s ease-out;
    }

    .fade-in.show {
      opacity: 1;
      transform: translateY(0);
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg fixed-top">
    <div class="container">
      <a class="navbar-brand" href="#">SMA N 9 Binsus Manado</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navmenu">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navmenu">
        <ul class="navbar-nav">
          <li class="nav-item"><a class="nav-link" href="#beranda">Beranda</a></li>
          <li class="nav-item"><a class="nav-link" href="#destinasi">Prestasi</a></li>
          <li class="nav-item"><a class="nav-link" href="#budaya">Budaya</a></li>
          <li class="nav-item"><a class="nav-link" href="#galeri">Galeri</a></li>
          <li class="nav-item"><a class="nav-link" href="#kontak">Kontak</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero -->
  <section id="beranda" class="hero">
    <div class="hero-content">
      <h1>Selamat Datang di SMA N 9 Binsus Manado</h1>
      <p>Sekolah dengan segudang prestasi di Sulawesi Utara</p>
      <a href="#destinasi" class="btn btn-primary btn-lg">Jelajahi Sekarang</a>
    </div>
  </section>

  <!-- Prestasi Section -->
  <section id="destinasi" class="fade-in">
    <div class="container">
      <h2>Prestasi Unggulan</h2>
      <div class="row g-4">
        <div class="col-md-4">
          <div class="card">
            <img src="https://i.ibb.co.com/cScQwxS8/dc9460e0-b41e-43e3-b76e-e155378da6df.jpg" class="card-img-top" alt="Akademik">
            <div class="card-body">
              <h5 class="card-title">Prestasi Akademik</h5>
              <p class="card-text">Siswa SMA N 9 Binsus Manado meraih berbagai penghargaan olimpiade tingkat nasional dan provinsi setiap tahunnya.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <img src="https://i.ibb.co.com/rGcqng0r/023a4903-7a6e-4291-8525-cc287ab1ac54.jpg" class="card-img-top" alt="Olahraga">
            <div class="card-body">
              <h5 class="card-title">Prestasi Non-Akademik</h5>
              <p class="card-text">Sekolah ini dikenal unggul dalam bidang olahraga, seni, dan debat. Banyak siswa yang menjadi juara di berbagai kompetisi.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <img src="https://i.ibb.co.com/N2y5Jn5t/563efb9f-e76b-4158-ae10-011a08acc8fa.jpg" class="card-img-top" alt="Kreativitas">
            <div class="card-body">
              <h5 class="card-title">Kreativitas & Inovasi</h5>
              <p class="card-text">SMA N 9 Binsus Manado mendorong siswanya untuk berinovasi dalam teknologi, sains, dan kewirausahaan.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Budaya Section -->
  <section id="budaya" class="bg-light fade-in">
    <div class="container">
      <h2>Budaya & Tradisi Sekolah</h2>
      <div class="row justify-content-center">
        <div class="col-md-8">
          <p class="lead text-center">
            SMA N 9 Binsus Manado menjunjung tinggi nilai-nilai budaya lokal yang ramah, santun, dan penuh semangat.  
            Setiap tahun, sekolah ini mengadakan <strong>Festival Pesona Sekolah Manado</strong> untuk memperkenalkan budaya, bahasa, dan kreativitas siswa kepada masyarakat luas.
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- Galeri Section -->
  <section id="galeri" class="fade-in">
    <div class="container">
      <h2>Galeri Sekolah</h2>
      <div id="carouselExample" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="https://ibb.co.com/bjt9RfHb"><img src="https://i.ibb.co.com/RG8w45hj/0917d098-c5b9-47af-ae43-6cb159de0f08.jpg" class="d-block w-100" alt="Sekolah">
          </div>
          <div class="carousel-item">
            <img src="https://i.ibb.co.com/cczxN0G6/036b355d-c589-4140-a4e4-37a6a20aaeba.jpg" class="d-block w-100" alt="Ekstrakurikuler">
          </div>
          <div class="carousel-item">
            <img src="https://i.ibb.co.com/35HXR2HD/ece73704-ea72-45aa-8f91-e49754c123e8.jpg" class="d-block w-100" alt="Kegiatan Sekolah">
          </div>
          <div class="carousel-item">
            <img src="https://i.ibb.co.com/XxBgrKq8/78e971b9-87fa-4209-b554-b966c964950c.jpg"  class="d-block w-100" alt="on ol">
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
          <span class="carousel-control-prev-icon"></span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
          <span class="carousel-control-next-icon"></span>
        </button>
      </div>
    </div>
  </section>

  <!-- Kontak Section -->
  <section id="kontak" class="bg-light fade-in">
    <div class="container">
      <h2>Hubungi Kami</h2>
      <div class="row justify-content-center">
        <div class="col-md-6">
          <form>
            <div class="mb-3">
              <label for="nama" class="form-label">Nama</label>
              <input type="text" class="form-control" id="nama" placeholder="Nama Anda">
            </div>
            <div class="mb-3">
              <label for="email" class="form-label">Email</label>
              <input type="email" class="form-control" id="email" placeholder="nama@email.com">
            </div>
            <div class="mb-3">
              <label for="pesan" class="form-label">Pesan</label>
              <textarea class="form-control" id="pesan" rows="4" placeholder="Tulis pesan Anda..."></textarea>
            </div>
            <button type="submit" class="btn btn-primary w-100">Kirim Pesan</button>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p><strong>SMA N 9 Binsus Manado</strong> © 2025 | Sekolah Unggulan di Sulawesi Utara</p>
    <div>
      <a href="https://sma9manado.sch.id/">Website Resmi</a> |
      <a href="https://sma9manado.sch.id/">Instagram</a> |
      <a href="https://sma9manado.sch.id/">Facebook</a>
    </div>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  <script>
    // Animasi fade-in saat scroll
    const faders = document.querySelectorAll('.fade-in');
    const appearOptions = { threshold: 0.2 };

    const appearOnScroll = new IntersectionObserver((entries, observer) => {
      entries.forEach(entry => {
        if (!entry.isIntersecting) return;
        entry.target.classList.add('show');
        observer.unobserve(entry.target);
      });
    }, appearOptions);

    faders.forEach(fader => {
      appearOnScroll.observe(fader);
    });
  </script>
</body>
</html>
