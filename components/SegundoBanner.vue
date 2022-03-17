<template>
  <div class="cont-banner">
    <div class="banner">
      <div class="izq-banner">
        <img src="promocional imag1.png" />
      </div>

      <div class="der-banner">
        <div class="der-banner-h1"><h1>NUESTROS PLANES EXEQUIALES</h1></div>
        <div class="der-banner-h2">
          <h2>UNIDOS, FRATERNAL, OLIHUELLITAS Y HUELLITAS ÚNICO.</h2>
        </div>
        <div class="der-banner-p">
          <p>
            Te ofrecen: 10% de descuento, 1 y hasta 2 meses gratis por afiliarte
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "PrimerBanner",
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
.banner {
  width: 100%;
  display: flex;
  text-align: center;
}
.izq-banner {
  width: 50%;
}
.izq-banner img {
  width: 100%;
  margin: 0px auto;
  padding-top: 30px;
}
.der-banner {
  width: 50%;
  padding-top: 150px;
}
.der-banner-h1 {
  width: 50%;
  margin: 0px auto;
  padding-bottom: 40px;
}
.der-banner-h2 {
  padding-bottom: 40px;
}
.der-banner-p {
  width: 60%;
  margin: 0px auto;
}
.der-banner h1,
h2,
p {
  color: #fb5e3b;
}
.der-banner p {
  font-size: 20px;
}
@media (max-width: 768px) {
  .banner {
    width: 100%;
    display: block;
    text-align: center;
  }
  .izq-banner {
    width: 100%;
  }
  .izq-banner img {
    width: 100%;
  }
  .der-banner {
    width: 100%;
    padding-top: 30px;
  }
  .der-banner-h1 {
    width: 100%;
    margin: 0px auto;
  }
  .der-banner-h2 {
    width: 90%;
    font-size: 15px;
    font-weight: 90;
    margin: 0px auto;
  }
  .der-banner-p {
    width: 80%;
    margin: 0px auto;
    font-size: 20px;
  }
  .der-banner h1,
  h2,
  p {
    color: #fb5e3b;
  }
}
</style>