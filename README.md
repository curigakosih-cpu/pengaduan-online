<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Pusat Layanan Pengaduan Penipuan Online</title>

<style>
body {
  margin:0;
  font-family: Arial, sans-serif;
  background:#f2f2f2;
}

/* HEADER */
header {
  background:#b30000;
  color:white;
  padding:15px;
}

.logo {
  font-size:20px;
  font-weight:bold;
}

.subtitle {
  font-size:14px;
  opacity:0.9;
}

/* NAV */
nav {
  background:#222;
  color:white;
  padding:10px;
  text-align:center;
}

/* CONTENT */
.container {
  max-width:1000px;
  margin:auto;
  padding:20px;
}

.card {
  background:white;
  padding:20px;
  margin-bottom:20px;
  border-radius:6px;
  box-shadow:0 2px 6px rgba(0,0,0,0.1);
}

h2 {
  color:#b30000;
  border-bottom:2px solid #eee;
  padding-bottom:5px;
}

input, textarea {
  width:100%;
  padding:10px;
  margin:6px 0 12px;
  border:1px solid #ccc;
  border-radius:4px;
}

button {
  background:#b30000;
  color:white;
  padding:12px;
  border:none;
  border-radius:4px;
  font-size:16px;
  cursor:pointer;
}

button:hover {
  background:#900000;
}

.whatsapp {
  background:#25D366;
}

.warning {
  background:#fff3cd;
  padding:12px;
  border-left:5px solid orange;
  font-weight:bold;
}

/* FOOTER */
footer {
  background:#222;
  color:white;
  text-align:center;
  padding:15px;
  font-size:14px;
}
</style>
</head>

<body>

<header>
<div class="logo">⚖️ LEMBAGA LAYANAN HUKUM NASIONAL</div>
<div class="subtitle">Pusat Resmi Pengaduan Penipuan Online</div>
</header>

<nav>
Perlindungan Korban • Layanan Publik • Pengaduan Digital
</nav>

<div class="container">

<div class="card">
<h2>Form Pengaduan Resmi</h2>

<form name="laporan"
method="POST"
data-netlify="true"
data-netlify-notify="true"
enctype="multipart/form-data">

<input type="hidden" name="form-name" value="laporan">

<label>Nama lengkap pelapor</label>
<input type="text" name="nama" required>

<label>Nomor WhatsApp</label>
<input type="text" name="wa" required>

<label>Tanggal kejadian</label>
<input type="date" name="tanggal">

<label>Kronologi kejadian</label>
<textarea name="kronologi" rows="5"></textarea>

<label>Rekening / identitas pelaku</label>
<input type="text" name="pelaku">

<label>Upload bukti transfer</label>
<input type="file" name="bukti">

<button type="submit">Kirim Laporan Resmi</button>

</form>
</div>

<div class="card warning">
⚠️ Layanan ini GRATIS  
⚠️ Tidak ada biaya pemulihan dana  
⚠️ Hati-hati pihak yang mengatasnamakan lembaga
</div>

<div class="card">
<h2>Hubungi Petugas</h2>
<a href="https://wa.me/6285827604032">
<button class="whatsapp">Chat WhatsApp Admin</button>
</a>
</div>

</div>

<footer>
© Layanan Pengaduan Penipuan Online  
Koesuma Hadi Suetomo, SH., MH.
</footer>

</body>
</html>
