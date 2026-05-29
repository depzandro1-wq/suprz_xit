<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>suprz xiter Store</title>
<style>
  *{margin:0;padding:0;box-sizing:border-box;font-family:'Segoe UI',sans-serif}
  body{background:#0a0a0f;color:#fff}
  header{padding:20px 5%;display:flex;justify-content:space-between;align-items:center;border-bottom:1px solid #1e1e2e}
  .logo{font-weight:700;font-size:22px;color:#a855f7}
  nav a{color:#ccc;margin-left:20px;text-decoration:none;transition:.3s}
  nav a:hover{color:#a855f7}
  .hero{padding:80px 5%;text-align:center;background:radial-gradient(circle at center, #1e1e2e 0%, #0a0a0f 70%)}
  .hero h1{font-size:42px;margin-bottom:15px}
  .hero p{color:#aaa;margin-bottom:25px}
  .btn{padding:12px 28px;background:#a855f7;border:none;border-radius:8px;color:#fff;font-weight:600;cursor:pointer;transition:.3s}
  .btn:hover{box-shadow:0 0 20px #a855f7}
  .products{padding:60px 5%}
  .products h2{text-align:center;margin-bottom:40px;font-size:28px}
  .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:25px}
  .card{background:#111118;border:1px solid #1e1e2e;border-radius:12px;padding:15px;transition:.3s}
  .card:hover{transform:translateY(-5px);border-color:#a855f7;box-shadow:0 0 15px rgba(168,85,247,.4)}
  .card img{width:100%;border-radius:8px;margin-bottom:12px}
  .card h3{font-size:18px;margin-bottom:8px}
  .card p{color:#aaa;font-size:14px;margin-bottom:10px}
  .price{color:#a855f7;font-weight:700}
  footer{padding:30px 5%;text-align:center;border-top:1px solid #1e1e2e;color:#666;font-size:14px}
  @media(max-width:600px){.hero h1{font-size:28px}}
</style>
</head>
<body>

<header>
  <div class="logo">suprz xiter</div>
  <nav>
    <a href="#">Home</a>
    <a href="#produk">Produk</a>
    <a href="#kontak">Kontak</a>
  </nav>
</header>

<section class="hero">
  <h1>Level Up Gear Kamu</h1>
  <p>Item gaming premium dengan aura mistis ungu 🔮</p>
  <button class="btn" onclick="document.getElementById('produk').scrollIntoView()">Lihat Produk</button>
</section>

<section class="products" id="produk">
  <h2>Produk Unggulan</h2>
  <div class="grid">
    <div class="card">
      <img src="https://via.placeholder.com/300x200/1e1e2e/a855f7?text=Item+1" alt="Produk 1">
      <h3>Xiter Blade</h3>
      <p>Skin eksklusif dengan efek aura ungu</p>
      <div class="price">Rp 99.000</div>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/300x200/1e1e2e/a855f7?text=Item+2" alt="Produk 2">
      <h3>Purple Aura Pack</h3>
      <p>Bundle efek + avatar serem</p>
      <div class="price">Rp 149.000</div>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/300x200/1e1e2e/a855f7?text=Item+3" alt="Produk 3">
      <h3>VIP Access</h3>
      <p>Akses semua fitur premium</p>
      <div class="price">Rp 299.000</div>
    </div>
  </div>
</section>

<footer id="kontak">
  © 2026 suprz xiter. Dibuat dengan aura mistis 💜
</footer>

</body>
</html>
