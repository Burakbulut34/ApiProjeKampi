<!doctype html>
<html lang="tr">
<head>
  <meta charset="utf-8">
  <title>ApiProjeKampi.WebApi - Mimari</title>
  <style>
    body { font-family: 'Segoe UI', sans-serif; background:#f9fafb; color:#111; margin:0; padding:20px; }
    h1 { text-align:center; margin-bottom:20px; }
    .container { max-width:900px; margin:0 auto; }
    .grid { display:grid; grid-template-columns:1fr 1fr; gap:16px; }
    .card { background:white; padding:16px; border-radius:10px; box-shadow:0 4px 10px rgba(0,0,0,0.05); }
    .card h2 { margin-top:0; color:#2563eb; font-size:18px; }
    .card p { margin:6px 0; font-size:14px; color:#444; }
    footer { text-align:center; margin-top:20px; font-size:13px; color:#666; }
  </style>
</head>
<body>
  <div class="container">
    <h1>📂 ApiProjeKampi.WebApi - Katmanlı Mimari</h1>
    
    <div class="grid">
      <div class="card">
        <h2>Context</h2>
        <p>DbContext sınıfı ve veritabanı bağlantıları burada tutulur.</p>
      </div>
      <div class="card">
        <h2>Controllers</h2>
        <p>API uç noktalarının bulunduğu controller sınıfları.</p>
      </div>
      <div class="card">
        <h2>Dtos</h2>
        <p>Veri transfer objeleri (istek/yanıt modelleri).</p>
      </div>
      <div class="card">
        <h2>Entities</h2>
        <p>Veritabanı tablolarını temsil eden sınıflar.</p>
      </div>
      <div class="card">
        <h2>Mapping</h2>
        <p>AutoMapper profilleri (DTO ↔ Entity dönüşümleri).</p>
      </div>
      <div class="card">
        <h2>Migrations</h2>
        <p>EF Core migration dosyaları, veritabanı güncellemeleri.</p>
      </div>
      <div class="card">
        <h2>ValidationRules</h2>
        <p>FluentValidation veya özel doğrulama kuralları.</p>
      </div>
      <div class="card">
        <h2>Program.cs</h2>
        <p>Uygulamanın giriş noktası, servisler ve middleware tanımları.</p>
      </div>
      <div class="card">
        <h2>appsettings.json</h2>
        <p>Konfigürasyon dosyası (DB bağlantısı, JWT, vs.).</p>
      </div>
    </div>
    
    <footer>© 2025 ApiProjeKampi.WebApi - Katmanlı Mimari Örneği</footer>
  </div>
</body>
</html>
