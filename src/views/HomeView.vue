<template>
  <container>
  <div class="OnPage"></div>
  <div class="OnPageSecond">
    <button class="btn-one">KEMBALI KE PILIHANKU</button>
  </div>
  <div>
    <img class="img-logo" src="../assets/logo.png" alt="logo">
    <h4 style="color: #314f95; position: relative; bottom: 8em;">DAPATKAN ASURANSI GRATIS DARI AXA LIFE INDONESIA</h4>
    <h3 style="color: #314f95; font-size: 28px; position: relative; bottom: 4em; display: inline;">UNTUK PEMEGANG KARTU KREDIT</h3>
    <img style="width: 95%; position: relative; top: -5em;" src="../assets/slides.png" alt="slides">
    <h3 style="position: relative; top: -3em; font-size: 26px;">Keuntungan mendaftar <span style="color: #325095;"> Axa life Indonesia </span>di Pilihkartu</h3>
    <div class="point">
      <div class="section-left">
        <section>
          <p>Diberikan gratis secara cuma-cuma tanpa premi
          <br> <span style="font-weight: bold;"> PREMI: 0 RP.0,-(NOL RUPIAH)</span>
          </p>
          <img src="../assets/icon_6.png" alt="icon_6">
        </section>
        <section>
          <p>
            Santunan meninggal dunia akibat kecelakaan <br> sebesar 
            <span style="font-weight: bold;">RP 25.000.000,-</span>
            (dua puluh lima juta rupiah)
          </p>
          <img src="../assets/icon_2.png" alt="icon_2">
        </section>
        <section>
          <p>
            Perlindungan <span style="font-weight: bold;">Asuransi Gratis</span> akan diberikan kepada pemegang
            <br>kartu kredit yang mendaftar program AXA Care Protection melalui <br> Pilihkartu.com
          </p>
          <img src="../assets/icon_3.png" alt="icon_3">
        </section>
    </div>
    <div class="section-right">
      <section>
        <p>
          Pendaftaran yang lolos verifikasi dari tim AXA berhak mendapatkan 
          <br> perlindungan Asuransi Kecelakaan diri<span style="font-weight: bold;">selama 3 bulan</span>
        </p>
        <img src="../assets/icon_4.png" alt="icon_4">
      </section>
      <section>
        <p>
          <span style="font-weight: bold;">Tanpa masa tunggu</span> perlindungan yang didapatkan 
          <br>dimulai sejak polis aktif
        </p>
        <img src="../assets/icon_5.png" alt="icon_5">
      </section>
      <section>
        <p>
          <span style="font-weight: bold;">Bukan penawaran</span> melainkan pemberian secara cuama-cuma 
          <br>kepada nasabah ter-registrasi via Pilihkartu.com 
          <br>yang sudah memiliki kartu kredit
        </p>
        <img src="../assets/icon_6.png" alt="icon_6">
      </section>
    </div>
    </div>
    </div>
  <div class="about">
    <h2 style="font-size: x-large; padding: 2em;">Tentang <span style="color: #325095;"> Axa Protection</span> Sekarang</h2>
    <p style="width: 80%; text-align: center; padding: 0em 0em 1em 10em;">
      Program asuransi gratis AXA Care Protection merupakan program perlindungan berupa asuransi 
      kecelakaan dari asuransi AXA Life Indonesia. Peserta yang lolos verifikasi akan mendapatkan 
      benefit berupa uang pertanggungan bila terjadi kecelakaan yang mengakibatkan meninggal dunia.
    </p>
    <button>DAFTAR SEKARANG JUGA</button>
  </div>
  <div>
    <form>
      <h3 style="font-size: x-large;font-weight: bold; padding-bottom: 1em;"> Dapatkan Perlindungan 
        <span style="color: #325095;">AXA Protection</span> Sekarang 
      </h3>
      <p style="font-weight: 700; padding-bottom: 1em;">Cukup isi data diri Anda pada form dibawah ini</p>
      <div class="form">
        <label >Nama Lengkap </label>
        <input type="text"><br><br>
        <label class="date">Tanggal Lahir (dd/mm/yy) </label> 
        <input type="date" value="hh-bb-tttt" > 
        <img src="../assets/icon_7.png" alt="icon_7" style=" position: relative; right: 8em; top: 3px;" width="15px" height="15px"><br><br>
        <label >Email</label>
        <input type="text"> <br><br>
        <label >Memiliki Kartu Kredit </label>
        <section class="checkbox">
          <input type="checkbox"> Visa
          <input type="checkbox"> MASTER CARD
          <input type="checkbox"> BCA CARD
          <input type="checkbox"> LAINNYA
          <div class="section-form" style="text-align: left; width: 450px; font-size: 14px ;position: relative; left: 24em; top: 1em;">
            <section style="text-decoration: underline; font-style: italic; padding-bottom: 1em;" > Syarat & Ketentuan Aplikasi</section>
            <input type="checkbox"> Saya mengetahui dan menyetujui syarat dan ketentuan diatas 
            serta bersedia dihubungi oleh PT. AXA Life Indonesia untuk mendapatkan penjelasan Tentang
            produk dan informasi laninnya
          </div>
          <button style="background-color:#26468f; color: white; padding: 15px 70px; position: relative; top: 2em; left: 5em; border: 1px solid #26468f;border-radius: 5px;">Kirim</button>
          </section>
      </div>
    </form>
  </div>
  <div><img src="../assets/langkah.png" alt="langkah"></div>
  <footer>
    <p>Copyright (c) 2017 Pilihkartucom and AXA All Rights Reserved</p>
  </footer>
</container>
  <router-view />
</template>

<script>
export default {
  
}
</script>

<style>
#app {
  text-align: center;
  
}
container{
  width: 100%;
  height: 100%;
}
*{
  margin: 0px !important;
  padding: 0px;
}
.OnPage{
  width: 100%;
  height: 30px;
  background-color: #26468f;
}
.btn-one{
  display: inline-block;
  position: relative;
  left: 30em;
  top: 1em;
  border-radius: 5px;
  padding: 20px 40px;
  background-color:#26468f; 
  color: white;
  font-size: 18px;
}
.img-logo{
  position: relative;
  right: 40em;
  bottom: 4em;
  display: inline;
}
.OnPageSecond{
  width: 100%;
  height: 100px;
  background-color: #ebebeb;

}
.point{
  width: 80%;
  display: inline-block;
  position: relative;
  top: -3em;
  
}
.point>section>p{
  display: inline-block;
}
.point>div>section>p{
  display: block;
  padding: 1em;
}
.point>.section-left>section>img{
  float: right;
  position: relative;
  bottom: 3em;
  right: 1em;
}
.point>.section-right>section>img{
  float: left;
  position: relative;
  bottom: 3em;
  left: 1em;
}
.section-left{
  width: 50%;
  display: inline-block;
}
.section-right{
  width: 50%;
  display: inline-block;
  position: relative;
}
.about{
  background-color: #f4f7fd;
  position: relative;
  top: -5em;
}
.about>button{
  background-color:#26468f; 
  color: white; 
  padding: 1em 3em; 
  position: relative; 
  top: 1em; 
  border-radius: 5px; 
  border-color: #26468f;
  font-weight: bold;
  font-size: medium;
}
.form{
  overflow: hidden;
  width: 50%;
  height: 20em;
  position: relative;
  left: 35em;
}
form>.form>label{
  float: left;
  width: 20em;
  padding-right: 1em;
  font-weight: bold;
  text-align: right;
  color: #3d4e5e;
}
form>.form>input[type=text],[type=date]{
  float: left;
  width: 20em;
  padding-right: 1em;
}
input[type=date]::-webkit-calendar-picker-indicator{
  opacity: 0;
}
input[type=date]{
  width: 20%;
}
.checkbox{
  padding-right: 4.5em;
}
footer{
  /* width: 100%; */
  height: 2em;
  background-color: #3d4e5e;
  text-align: center;
  padding-top: 0.5em;
  color: white;
  background-color: #26468f;
  position: relative;
  top: 1em;
}
</style>

<!-- <script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";

export default {
  // name: "HomeView",
  // components: {
  //   HelloWorld,
  // },
};
</script> -->