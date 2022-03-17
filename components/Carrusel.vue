<template>
  <v-carousel v-model="model">
    <v-carousel-item v-for="(color, i) in colors" :key="color">
      <v-sheet :color="color" height="100%" tile>
        <v-row class="fill-height" align="center" justify="center">
          <div class='container'>
              		<div class="banner">
			<div class="izq-banner">
				<div class="izq-banner-h1">
					<h1 class="h1-inside">Centro de ayuda psicológica <h1 class="mensSana">“Mens Sana”</h1></h1>
				</div>
				<img src="../assets/MENSSANA IMG1.png">
			</div>

			<div class="der-banner">
				<div class="der-banner-h1">
					<h1>Atención integral según las necesidades emocionales de nuestros afiliados:</h1>
				</div>
				<div class="cont-columnas">
					<div class="columna">
						<img src="seguridad a tu vida copia.png">
						<p>Programa de promoción y prevención en salud mental</p>
					</div>

					<div class="columna">
						<img src="mentorias.png">
						<p>Mentorías según sean los intereses de los afiliados</p>
					</div>

					<div class="columna">
						<img src="atencion psicologica.png">
						<p>Atención psicológica individual o familiar ante cualquier problema de consideración clínica</p>
					</div>
				</div>
			</div>
		</div>
          </div>
        </v-row>
      </v-sheet>
    </v-carousel-item>
  </v-carousel>
</template>


<script>
export default {
  data: () => ({
    model: 0,
    colors: ["primary", "secondary", "yellow darken-2", "red", "orange"],
  }),
};
</script>

<style>

</style>