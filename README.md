<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hotel Services</title>
  <link rel="stylesheet" href="style.css">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <header class="bg-dark text-white text-center py-4">
    <h1>Hotel Paradise</h1>
    <p>Tempat nyaman untuk istirahat Anda</p>
  </header>

  <main class="container mt-4">
   <div id="hotelCarousel" class="carousel slide" data-bs-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="bali.jpg" class="d-block w-100" alt="bali.jpg 1">
        </div>
        <div class="carousel-item">
          <img src="jakarta.jpg" class="d-block w-100" alt="jakarta.jpg2">
        </div>
        <div class="carousel-item">
          <img src="surabaya.jpg" class="d-block w-100" alt="surabaya.jpg.jpg">
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#hotelCarousel" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#hotelCarousel" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
    <section class="mt-4">
      <h2>About Us</h2>
      <p>Hotel Paradise adalah perusahaan penyedia layanan penginapan yang nyaman, aman, dan mewah untuk semua tamu kami.</p>
    </section>
   
    <section class="mt-4">
      <h2>Book Your Stay</h2>
      <form class="mb-4">
        <div class="mb-3">
          <label for="name" class="form-label">Name</label>
          <input type="text" class="form-control" id="name" placeholder="Enter your name">
        </div>
        <div class="mb-3">
          <label for="email" class="form-label">Email</label>
          <input type="email" class="form-control" id="email" placeholder="Enter your email">
        </div>
        <button type="submit" class="btn btn-primary">Submit</button>
      </form>
    </section>

    <section class="mt-4">
      <h2>Our Branches</h2>
      <table class="table table-bordered">
        <thead>
          <tr>
            <th>#</th>
            <th>Branch Name</th>
            <th>Location</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>1</td>
            <td>Paradise Bali</td>
            <td>Bali</td>
          </tr>
          <tr>
            <td>2</td>
            <td>Paradise Jakarta</td>
            <td>Jakarta</td>
          </tr>
          <tr>
            <td>3</td>
            <td>Paradise Surabaya</td>
            <td>Surabaya</td>
          </tr>
        </tbody>
      </table>
    </section>
  </main>

  <footer class="bg-dark text-white text-center py-3">
    <p>2024 Hotel Paradise. All Rights Reserved.</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
