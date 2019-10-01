Tahapan forking File

    Login akun yang telah dibuat.
    Cari link github repository yang telah dikirimkan.
    klik fork button di kanan atas di repository page dari akun tersebut.

Tahapan Commits di akun

    klik file yang telah di fork.
    klik tombol hijau "Add a Readme" di kanan bawah projek.
    Jika sudah selesai, klik tombol hijau "Commit new file"
Perubahan yang saya lakukan di Web JS, HTML dan CSS yaitu :
    perubahan warna CSS menjadi abu - abu
    perubahan pada script index.html pada canvas ukuran 1024 x 1024, perubahan nama title menjadi bulat bulat, perubahan warna font pada           heading dan marquee di teks Bulat Gan.
    perubahan pada untangle.data.js terdapat pada var circlesCount = 500; yang semula 1000
    perubahan pada untangle.drawing.js terletak pada var r=255*Math.random()|30, g=300*Math.random()|20,
    perubahan pada untangle.js yang saya ubah bagian membuka komentar pada 
    $(document).ready(function(){
  var canvas = document.getElementById("game");
  var ctx = canvas.getContext("2d");
  ctx.fillStyle = "yellow";
  ctx.beginPath();
  ctx.arc(60, 60, 50, 0, Math.PI*2, true);
  ctx.closePath();
  ctx.fill();

  ctx.fillStyle = "green";
  ctx.beginPath();
  ctx.arc(210, 100, 50, 0, Math.PI*2, true);
  ctx.closePath();
  ctx.fill();
  dan mengubah warna yang semula gold menjadi yellow dan arc nya juga diubah dua duanya.
