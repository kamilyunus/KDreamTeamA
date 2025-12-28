# KDreamTeamA
KDream Team One Stop Portal
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>FARMASI from Turkiye | Monthly Promos</title>
  <style>
    body { margin:0; font-family:Arial,Helvetica,sans-serif; background:#f7f7f7; color:#333; }
    header { background:linear-gradient(135deg,#7b1fa2,#9c27b0); color:white; padding:40px 20px; text-align:center; }
    header h1 { margin:0 0 10px; font-size:2.2em; }
    header p { margin:0; font-size:1.1em; }
    .lang-switch { text-align:center; margin-top:15px; }
    .lang-switch button { margin:0 5px; padding:8px 16px; border-radius:20px; border:none; cursor:pointer; font-weight:bold; }
    .active { background:#fff; color:#7b1fa2; }
    .inactive { background:rgba(255,255,255,0.3); color:white; }
    .container { max-width:1100px; margin:auto; padding:30px 20px; }
    .cta-buttons { display:flex; flex-wrap:wrap; gap:15px; justify-content:center; margin:30px 0; }
    .cta-buttons a { text-decoration:none; padding:14px 26px; border-radius:30px; font-weight:bold; transition:0.3s; }
    .btn-primary { background:#9c27b0; color:white; }
    .btn-primary:hover { background:#7b1fa2; }
    .btn-secondary { background:white; color:#9c27b0; border:2px solid #9c27b0; }
    .btn-secondary:hover { background:#f3e5f5; }
    h2 { text-align:center; margin-bottom:20px; }
    .promo-grid { display:grid; grid-template-columns:repeat(auto-fit,minmax(260px,1fr)); gap:20px; }
    .promo-card { background:white; border-radius:12px; padding:20px; box-shadow:0 4px 10px rgba(0,0,0,0.08); }
    .promo-card h3 { margin-top:0; color:#7b1fa2; }
    footer { background:#333; color:white; text-align:center; padding:20px; margin-top:40px; font-size:0.9em; }
  </style>
</head>
<body><header>
  <h1 data-en="FARMASI Brands" data-ms="Jenama FARMASI">FARMASI Brands</h1>
  <p data-en="Your Trusted Source for Beauty, Wellness & Lifestyle Products"
     data-ms="Sumber Dipercayai untuk Produk Kecantikan, Kesihatan & Gaya Hidup">
     Your Trusted Source for Beauty, Wellness & Lifestyle Products
  </p>
  <div class="lang-switch">
    <button id="btn-en" class="active" onclick="switchLang('en')">EN</button>
    <button id="btn-ms" class="inactive" onclick="switchLang('ms')">BM</button>
  </div>
</header><div class="container">  <div class="cta-buttons">
    <a href="https://www.farmasi.my/kamilyunus/package-selection" class="btn-primary" data-en="Sign Up as FARMASI Member" data-ms="Daftar Sebagai Ahli FARMASI">Sign Up as FARMASI Member</a>
    <a href="https://www.farmasi.my/kamilyunus/register/customer" class="btn-secondary" data-en="Become a Customer" data-ms="Daftar Sebagai Pelanggan">Become a Customer</a>
    <a href="https://www.farmasi.my/kamilyunus/catalog" class="btn-secondary" data-en="View Product Catalog" data-ms="Lihat Katalog Produk">View Product Catalog</a>
  </div>  <h2 data-en="Monthly Promotions" data-ms="Promosi Bulanan">Monthly Promotions</h2>  <div class="promo-grid">
    <div class="promo-card">
      <h3 data-en="January Promo" data-ms="Promosi Januari">January Promo</h3>
      <p data-en="Up to 30% OFF selected skincare & personal care items. Limited time only." 
         data-ms="Sehingga 30% DISKAUN untuk produk penjagaan kulit & diri terpilih. Tawaran terhad.">
         Up to 30% OFF selected skincare & personal care items. Limited time only.
      </p>
    </div><div class="promo-card">
  <h3 data-en="Beauty Bundle Deal" data-ms="Pakej Bundle Kecantikan">Beauty Bundle Deal</h3>
  <p data-en="Buy selected products and enjoy special bundle savings." 
     data-ms="Beli produk terpilih dan nikmati penjimatan istimewa.">
     Buy selected products and enjoy special bundle savings.
  </p>
</div>

<div class="promo-card">
  <h3 data-en="Wellness Specials" data-ms="Promosi Kesihatan">Wellness Specials</h3>
  <p data-en="Exclusive member prices on nutrition & wellness products." 
     data-ms="Harga istimewa ahli untuk produk nutrisi & kesihatan.">
     Exclusive member prices on nutrition & wellness products.
  </p>
</div>

  </div></div><footer>
  <p data-en="© 2025 FARMASI | Authorized Independent Influencer"
     data-ms="© 2025 FARMASI | Influencer Bebas Sah">© 2025 FARMASI | Authorized Independent Influencer</p>
  <p data-en="Malaysia • Original • Trusted" data-ms="Malaysia • Asli • Dipercayai">Malaysia • Original • Trusted</p>
</footer><script>
  function switchLang(lang) {
    document.querySelectorAll('[data-en]').forEach(el => {
      el.innerText = el.getAttribute('data-' + lang);
    });
    document.getElementById('btn-en').className = lang === 'en' ? 'active' : 'inactive';
    document.getElementById('btn-ms').className = lang === 'ms' ? 'active' : 'inactive';
  }
</script></body>
</html>
