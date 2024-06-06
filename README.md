
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>KJPP Hari Utomo dan Rekan</title>
  <link rel="stylesheet" href="https://diy.magis.unwahas.ac.id/AdminLTE/plugins/fontawesome-free/css/all.min.css">
  <link href="https://diy.magis.unwahas.ac.id/css/app.css" rel="stylesheet">
  <link rel="stylesheet" href="https://unpkg.com/leaflet@1.7.1/dist/leaflet.css"
    integrity="sha512-xodZBNTC5n17Xt2atTPuE1HxjVMSvLVW9ocqUKLsCC5CXdbqCmblAshOMAS6/keqq/sMZMZ19scR4PsZChSR7A=="
    crossorigin="" />
  <script src="https://unpkg.com/leaflet@1.7.1/dist/leaflet.js"
    integrity="sha512-XQoYMqMTK8LvdxXYG3nZ448hOEQiglfqkJs1NOQV44cWnUrBc8PkAOcXy20w0vlaXaVUearIOBhiXZ5V3ynxwA=="
    crossorigin=""></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/3.5.1/chart.js"></script>
  <!-- jQuery -->
  <script src="https://diy.magis.unwahas.ac.id/AdminLTE/plugins/jquery/jquery.min.js"></script>
  <!-- Bootstrap 4 -->
  <script src="https://diy.magis.unwahas.ac.id/AdminLTE/plugins/bootstrap/js/bootstrap.bundle.min.js"></script>
  <!-- DataTables -->
  <script src="https://diy.magis.unwahas.ac.id/AdminLTE/plugins/datatables/jquery.dataTables.min.js"></script>
  <script src="https://diy.magis.unwahas.ac.id/AdminLTE/plugins/datatables-bs4/js/dataTables.bootstrap4.min.js"></script>
  <script src="https://diy.magis.unwahas.ac.id/AdminLTE/plugins/datatables-responsive/js/dataTables.responsive.min.js"></script>
  <script src="https://diy.magis.unwahas.ac.id/AdminLTE/plugins/datatables-responsive/js/responsive.bootstrap4.min.js"></script>
</head>

<style>
  body {
    font-family: 'Montserrat', 'sans-serif';
  }
</style>
<div class="row mx-5 mt-3">
   <div class="col">
    <a href="GISKJPPHU.html" class="btn" style="background-color: #84C2D8; border-radius: 10px">Kembali</a>
   </div>
</div>
<div class="row mt-3 mx-5">
  <div class="col-sm-6">
    <div class="card">

      <div class="card-body">
        <h3 class="card-title">
          Peta
        </h3>
        <hr>
        <div id="map" style="width: 100%; height: 550px;"></div>
      </div>
    </div>
  </div>
  <div class="col-sm-6">
    <div class="card">
      <!-- /.card-header -->
      <div class="card-body">
        <h3 class="card-title">
      Gambar
        </h3>
        <hr>
        <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
          <ol class="carousel-indicators">
           <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
          </ol>
          <div class="carousel-inner">
                        <div class="carousel-item active" data-bs-interval="2000">
				<img class="d-block w-100" src="PERUM 1.png" alt="First slide">
            </div>
                      </div>
          <a class="carousel-control-prev" href="PERUM 2.png" role="button" data-slide="prev">
            <span class="carousel-control-custom-icon" aria-hidden="true">
              <i class="fas fa-chevron-left"></i>
            </span>
            <span class="sr-only">Previous</span>
          </a>
          <a class="carousel-control-next" href="PERUM 3.png" role="button" data-slide="next">
            <span class="carousel-control-custom-icon" aria-hidden="true">
              <i class="fas fa-chevron-right"></i>
            </span>
            <span class="sr-only">Next</span>
          </a>
        </div>
      </div>
      <!-- /.card-body -->
    </div>
  </div>
</div>
<div class="row mt-3 mx-5">
  <div class="col-md-6 ">
    <div class="card">
      <div class="card-header">
        <h3 class="card-title">Detail Objek</h3>
      </div>
      <!-- /.card-header -->
      <div class="card-body">
        <table class="table table-bordered">
          <thead>
			 <tr>
              <td> Lokasi  </td>
              <td>:</td>
              <td>Perum Green Garden Blok H.6 No.8, Kelurahan Kedoya Utara, Kecamatan Kebon Jeruk, Kota Jakarta Barat, Provinsi DKI Jakarta.</tr>
			 <tr>
              <td>Basis Nilai</td>
              <td>: </td>
              <td>Nilai Pasar dan Indikasi Nilai Likuidasi</td>
            </tr>
			<tr>
              <td>Tanggal Laporan</td>
              <td>: </td>
              <td>18 Januari 2022</td>
            </tr>
			<tr>
              <td>Tanggal Penilaian</td>
              <td>: </td>
              <td>19 Januari 2022</td>
            </tr>
			<tr>
              <td>Tahun Penilaian</td>
              <td>: </td>
              <td> 2022 </td>
            </tr>
			<tr>
              <td>Titik Koordinat</td>
              <td>:</td>
              <td><a href="https://www.google.com/maps/place/6%C2%B010'11.6%22S+106%C2%B045'22.1%22E/@-6.1698887,106.7535491,17z/data=!3m1!4b1!4m4!3m3!8m2!3d-6.169894!4d106.756124?entry=ttu">
       -6.169894, 106.756124 													
                  </a></td>
            </tr>
			<tr>
              <th>Jenis Data</th>
              <th style="width: 10px">:</th>
              <th>Rumah tinggal</th>
            </tr>
           <tr>
              <td>Luas Tanah Sertipikat</td>
              <td>:</td>
              <td>152 m2</td>
            </tr>
			<tr>
              <td>Luas Bangunan</td>
              <td>:</td>
              <td>216 m2</td>
            </tr>
			<tr>
              <td>Nilai Pnwrn/Transaksi</td>
              <td>:</td>
              <td> Rp. 3,339,380,000.-</td>
            </tr>
			<tr>
              <td>Indikasi Nilai Pasar Tanah/m2</td>
              <td>:</td>
              <td> Rp. 17,230,000.-</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
    <!-- /.card -->
 <div class="card">
      <div class="card-header">
        <h3 class="card-title">DATA Pembanding 1</h3>
      </div>
      <!-- /.card-header -->
      <div class="card-body">
        <table class="table table-bordered">

          <tbody>
			<tr>
              <td> Lokasi  </td>
              <td>:</td>
              <td> Perum Green Garden Blok H.1 No.14 </td>
            </tr>
			<tr>
              <td>Titik Koordinat</td>
              <td>:</td>
              <td><a href="https://www.google.com/maps/place/6%C2%B010'10.9%22S+106%C2%B045'19.0%22E/@-6.1697007,106.7527091,17z/data=!3m1!4b1!4m4!3m3!8m2!3d-6.169706!4d106.755284?entry=ttu">
         -6.169706, 106.755284 									
                  </a></td>
            </tr>
			<tr>
              <th>Jenis Data</th>
              <th style="width: 10px">:</th>
              <th>Rumah tinggal</th>
            </tr>
           <tr>
              <td>Nama Sumber Data</td>
              <td>:</td>
              <td> Agen properti </td>
            </tr>
			<tr>
              <td>No. Telp. Sumber Data </td>
              <td>: </td>
              <td>0811 133 425</td>
            </tr>
			<tr>
              <td>Luas Tanah Sertipikat</td>
              <td>:</td>
              <td>200 m2</td>
            </tr>
			<tr>
              <td>Luas Bangunan</td>
              <td>:</td>
              <td>250 m2</td>
            </tr>
			<tr>
              <td>Nilai Pnwrn/Transaksi</td>
              <td>:</td>
              <td> Rp. 4,500,000,000.-</td>
            </tr>
			<tr>
              <td>Indikasi Nilai Pasar Tanah/m2</td>
              <td>:</td>
              <td> Rp. 16,969,000.-</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
  <div class="col-md-6">
    <div class="card">
      <div class="card-header">
        <h3 class="card-title">DATA Pembanding 2</h3>
      </div>
      <!-- /.card-header -->
      <div class="card-body">
        <table class="table table-bordered">
          <tbody>
			<tr>
              <td> Lokasi  </td>
              <td>:</td>
              <td> Perum Green Garden Blok H.3 No.14 </td>
            </tr>
			<tr>
              <td>Titik Koordinat</td>
              <td>:</td>
              <td><a href="https://www.google.com/maps/place/6%C2%B010'13.8%22S+106%C2%B045'21.5%22E/@-6.1705017,106.7534061,17z/data=!3m1!4b1!4m4!3m3!8m2!3d-6.170507!4d106.755981?entry=ttu">
       -6.170507, 106.755981 						 										
                  </a></td>
            </tr>
			<tr>
              <th>Jenis Data</th>
              <th style="width: 10px">:</th>
              <th> Rumah tinggal </th>
            </tr>
			<tr>
              <td>Nama Sumber Data</td>
              <td>:</td>
              <td>Agen properti</td>
            </tr>
			<tr>
              <td>No. Telp. Sumber Data </td>
              <td>: </td>
              <td>0855 8081 707</td>
            </tr>
			<tr>
              <td>Luas Tanah Sertipikat</td>
              <td>:</td>
              <td>300 m2</td>
            </tr>
			<tr>
              <td>Luas Bangunan</td>
              <td>:</td>
              <td>350 m2</td>
            </tr>
			<tr>
              <td>Nilai Pnwrn/Transaksi</td>
              <td>:</td>
              <td> Rp. 6,500,000,000.-</td>
            </tr>
			<tr>
              <td>Indikasi Nilai Pasar Tanah/m2</td>
              <td>:</td>
              <td> Rp. 17,126,000.-</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
    <!-- /.card -->
    <div class="card">
      <div class="card-header">
        <h3 class="card-title">DATA Pembanding 3</h3>
      </div>
      <!-- /.card-header -->
      <div class="card-body">
        <table class="table table-bordered">
         <tbody>
			<tr>
              <td> Lokasi  </td>
              <td>:</td>
              <td> Perum Green Garden Blok F.1 No.5-6 </td>
            </tr>
			<tr>
              <td>Titik Koordinat</td>
              <td>:</td>
              <td><a href="https://www.google.com/maps/place/6%C2%B010'03.6%22S+106%C2%B045'22.2%22E/@-6.1676477,106.7536011,17z/data=!3m1!4b1!4m4!3m3!8m2!3d-6.167653!4d106.756176?entry=ttu">
     -6.167653, 106.756176 						
                  </a></td>
            </tr>
			<tr>
              <th>Jenis Data</th>
              <th style="width: 10px">:</th>
              <th>Rumah Tinggal</th>
            </tr>
           <tr>
              <td>Nama Sumber Data</td>
              <td>:</td>
              <td> Agen properti </td>
            </tr>
			<tr>
              <td>No. Telp. Sumber Data </td>
              <td>: </td>
              <td>0853 7707 7053</td>
            </tr>
			<tr>
              <td>Luas Tanah Sertipikat</td>
              <td>:</td>
              <td>600 m2</td>
            </tr>
			<tr>
              <td>Luas Bangunan</td>
              <td>:</td>
              <td>750 m2</td>
            </tr>
			<tr>
              <td>Nilai Pnwrn/Transaksi</td>
              <td>:</td>
              <td> Rp. 15,000,000,000.-</td>
            </tr>
			<tr>
              <td>Indikasi Nilai Pasar Tanah/m2</td>
              <td>:</td>
              <td> Rp. 18,531,000.-</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
          </tbody>
        </table>
      </div>
    </div>
  </div>
</div>
  

<script>
  var peta1 = L.tileLayer('https://api.mapbox.com/styles/v1/{id}/tiles/{z}/{x}/{y}?access_token=pk.eyJ1IjoibWFwYm94IiwiYSI6ImNpejY4NXVycTA2emYycXBndHRqcmZ3N3gifQ.rJcFIG214AriISLbB6B5aw', {
            attribution: 'Map data &copy; <a href="https://www.openstreetmap.org/">OpenStreetMap</a> contributors, ' +
                '<a href="https://creativecommons.org/licenses/by-sa/2.0/">CC-BY-SA</a>, ' +
                'Imagery © <a href="https://www.mapbox.com/">Mapbox</a>',
            id: 'mapbox/streets-v11'
        });
    
    
        var map = L.map('map', {
            center: [-7.9409693,110.5509868],
            zoom: 14,
            layers: [peta1],
        });
    
        var baseMaps = {
            "Grayscale": peta1,
           
        };
    
        L.control.layers(baseMaps).addTo(map);



        var iconsekolah = L.icon({
            iconUrl: 'OBJEK PERUM.png',
            iconSize:     [300, 300],        
        });

		var informasi = '<table class="table table-bordered"> <tr><td colspan="2"><a href="https://www.google.com/maps/dir//-7.9409693,110.5509868" class="btn btn-sm btn-default">Rute</a></td></tr></body></table>';
         L.marker([-7.9409693,110.5509868],{icon: iconsekolah})
        // .bindPopup(L.popup({maxWidth:500}).setContent('<a href="https://www.google.com/maps/dir//-7.9409693,110.5509868" target="_blank">Rute Ke Lokasi</a>'))
		 .addTo(map);
</script>
