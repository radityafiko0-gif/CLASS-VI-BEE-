<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<title>Kelas VI B</title>
<meta name="viewport" content="width=device-width, initial-scale=1">

<style>

body{
font-family:Arial;
margin:0;
background:linear-gradient(135deg,#1e3c72,#2a5298);
color:white;
}

/* HEADER */
header{
text-align:center;
padding:80px 20px;
background:rgba(0,0,0,0.4);
}

header img{
width:90%;
max-width:900px;
border-radius:20px;
box-shadow:0 10px 30px black;
}

h1{
margin-top:20px;
font-size:40px;
}

section{
padding:40px;
}

/* CARD */
.card{
background:white;
color:black;
padding:25px;
border-radius:15px;
margin:20px auto;
max-width:900px;
box-shadow:0 10px 25px rgba(0,0,0,0.3);
}

/* STRUKTUR */
.struktur{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(150px,1fr));
gap:15px;
text-align:center;
}

/* PIKET */
button{
width:100%;
padding:12px;
margin:5px 0;
border:none;
border-radius:10px;
background:#2a5298;
color:white;
font-size:16px;
cursor:pointer;
}

button:hover{
background:#1e3c72;
}

/* JADWAL */
table{
width:100%;
border-collapse:collapse;
}

td,th{
border:1px solid #ddd;
padding:10px;
text-align:center;
}

/* FOTO */
.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:15px;
}

.gallery img{
width:100%;
border-radius:15px;
box-shadow:0 5px 15px black;
}

/* VIDEO */
video{
width:100%;
border-radius:15px;
}

/* MAP */
iframe{
width:100%;
height:350px;
border-radius:15px;
border:none;
}

/* TIKTOK */
.tiktok{
text-align:center;
margin-top:20px;
}

.tiktok a{
background:black;
color:white;
padding:12px 20px;
border-radius:10px;
text-decoration:none;
}

</style>
</head>

<body>

<header>

<img src="foto-awal.jpg">

<h1>KELAS VI B</h1>
<p>SDN Kalinegoro 03</p>

</header>

<section>

<div class="card">

<h2>Struktur Kelas</h2>

<div class="struktur">

<div>
<b>Ketua</b>
<p>Nama Ketua</p>
</div>

<div>
<b>Wakil Ketua</b>
<p>Nama Wakil</p>
</div>

<div>
<b>Sekretaris</b>
<p>Nama Sekretaris</p>
</div>

<div>
<b>Bendahara</b>
<p>Nama Bendahara</p>
</div>

<div>
<b>Wali Kelas</b>
<p>Nama Guru</p>
</div>

</div>

</div>

<div class="card">

<h2>Jadwal Piket</h2>

<button onclick="alert('Petugas: A, B, C')">Senin</button>
<button onclick="alert('Petugas: D, E, F')">Selasa</button>
<button onclick="alert('Petugas: G, H, I')">Rabu</button>
<button onclick="alert('Petugas: J, K, L')">Kamis</button>
<button onclick="alert('Petugas: M, N, O')">Jumat</button>

</div>

<div class="card">

<h2>Jadwal Pelajaran</h2>

<table>

<tr>
<th>Hari</th>
<th>Pelajaran</th>
</tr>

<tr>
<td>Senin</td>
<td>MTK, Bahasa Indonesia, Bahasa Inggris</td>
</tr>

<tr>
<td>Selasa</td>
<td>Bahasa Indonesia, PJOK, Matematika</td>
</tr>

<tr>
<td>Rabu</td>
<td>PAI, Matematika, IPAS</td>
</tr>

<tr>
<td>Kamis</td>
<td>IPAS, PPKn, Seni</td>
</tr>

<tr>
<td>Jumat</td>
<td>BTQ, Bahasa Jawa</td>
</tr>

</table>

</div>

<div class="card">

<h2>Album Kelas</h2>

<div class="gallery">

<img src="foto1.jpg">
<img src="foto2.jpg">

</div>

</div>

<div class="card">

<h2>Video Kelas</h2>

<video controls>
<source src="video.mp4">
</video>

</div>

<div class="card">

<h2>Lokasi Sekolah</h2>

<iframe src="https://maps.google.com/maps?q=SDN%20Kalinegoro%2003&t=&z=15&ie=UTF8&iwloc=&output=embed"></iframe>

</div>

<div class="tiktok">

<a href="https://www.tiktok.com/@classvibee3?_r=1&_t=ZS-94S9pUT1dLE">TikTok Kelas</a>

</div>

</section>

</body>
</html>
