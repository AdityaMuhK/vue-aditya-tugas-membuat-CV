<template>
    <div class="container background">
        <h1 class="title"><b>TUGAS CV ADITYA</b></h1>
            <div class="row">
                <div class="column">
                    <div class="card">
                <img src="../assets/1000_F_353110097_nbpmfn9iHlxef4EDIhXB1tdTD0lcWhG9.jpg" alt="Avatar" style="width:100%">
                    <div class="container title">
                        <h4><b>Aditya Muhammad Kurniawan</b></h4> 
                        <p>sekolah: SMK Bina Nusantara</p>
                        <p>kelas: 10</p>
                        <p>agama: Islam</p>
                        <p>kewarganegaraan: Warga Negara Indonesia</p>
                        <p>gender: Laki-laki</p>
                        <p>Tempat tgl lahir: Grobogan, 19-12-2006</p>
                        <p>Alamat sekarang: Ivory Park</p>
                        <p>telephone: 081225628834</p>
                        <p>email: adityamuhammadk@gmail.com</p>
                        </div>
                    </div>
            </div>
        <div class="column">
            <div class="card2">
                <div class="container2">
                    <h2 class="title2">PENDIDIKAN</h2>
                    <h4 class="title"><b>FORMAL</b></h4>
                    <ul class="title">
                      <li>2012 - 2018 MI Roudlotus Syubban</li>
                      <li>2019 - 2021 SMP PGRI 01 Semarang</li>
                      <li>2021 - sekarang SMK Bina Nusantara Mranggen</li>
                    </ul>
                    <h4 class="title"><b>INFORMAL</b></h4>
                </div>
            <hr class="new5">
            <div class="container2">
                <h2 class="title2">KEMAMPUAN</h2>
                    <ul class="title">
                        <li>HTML,CSS,Javascript,Node JS,Bootstrap</li>
                        <li>Mendesain dan Editing video</li>
                        <li>berbahasa jepang(sedikit)</li>
                    </ul>
            </div>
            <hr class="new5">
            <div class="container2">
                <h2 class="title2">PENGALAMAN KERJA</h2>
                    <ul class="title">
                        <li>Mengamplas dan Mengecat Truck di Astra UD Truck</li>
                        <li>Berjualan Makanan di sekolahan</li>
                        <li>menjual sembako dirumah</li>
                        <li>Berjualan makanan dirumah (pecel,gorengan,nugget)</li>
                    </ul>
            </div>
        </div>
    </div>
    </div>
</div>

</template>

<script>

</script>

<style>
.background{
    border: 5px solid rgba(0, 65, 245, 0.959);
    border-radius: 18px;
    background: linear-gradient(to bottom right, #0099cc 0%, #ffffff 100%);
}
.bungkus{
    display: block;
}
.title{
    text-align: left;
    font-family: cursive;
}
.title2{
    font-family: cursive;
}
.card {
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  transition: 0.3s;
  width: 120%;
  margin-left: 20%;
  margin-top: 10%;
  background: linear-gradient(to top, #3399ff 0%, #ffffff 100%);
}

.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}

.container {
  padding: 2px 16px;
}
.card2{
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  transition: 0.3s;
  width: 500px;
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
  padding: 5px;
  margin-top: 10%;
  margin-left: 200px;
  background: linear-gradient(to top, #0099cc 0%, #ffffff 100%);
  border-radius: 5px;
}
.container2 {
  padding: 5px;
}
.card2:hover {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}
h2{
    text-align: center;
    color: aqua;
}
li{
    padding: 10px 15px;
}
.glow {
  font-size: 80px;
  color: #fff;
  text-align: center;
  animation: glow 1s ease-in-out infinite alternate;
}
.column {
  float: left;
  width: 25%;
  padding: 0 10px;
}

.row {margin: 0 -5px;}

.row:after {
  content: "";
  display: table;
  clear: both;
}
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
    display: block;
    margin-bottom: 20px;
  }
}
hr.new5 {
  border: 5px solid rgb(255, 3, 3);
  border-radius: 100px;
}
</style>