<template>
		<div class="banner">
			<div class="izq-banner">
				<div class="izq-banner-h1">
					<h1 class="h1-inside">Centro de ayuda psicológica <h1 class="mensSana">“Mens Sana”</h1></h1>
				</div>
				<img src="MENSSANA IMG1.png">
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
</template>

<script>
export default {
    name:'PrimerBanner'
}
</script>

<style>
*{
    margin:0; padding:0;
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
}

.banner{
    height: 500px;
    margin:10px;
    display: flex;
    align-items: center;
    justify-content: center;

}
.banner .izq-banner{
    display: block;
    padding:15px;
    text-align: center;
    width: 40%;
    height: 100%;
}
.banner .izq-banner .izq-banner-h1{
    width: 50%;
    height: 30%;
    color: #023B4F;
}
.banner .izq-banner .mensSana{
    width: 100%;
    height: 30%;
    color: #FD8F16;
}
.banner .izq-banner img{
    width:100%;
    height: 350px;
    transform: rotate(5deg);
}
    .banner .der-banner{
        position: relative;
        bottom: -33px;
        padding:10px;
        display: flex;
        width: 60%;
        height: 100%;
        display: block;
        text-align: center;
    }
    .banner .der-banner .der-banner-h1{
        width: 70%;
        height: 40%;
        color: #FD8F16;
        padding-top: 40px;
        align-items: center;
        margin: 0px auto;
    }
    .banner .der-banner .cont-columnas{
        width: 100%;
        display: flex;
    }
    .banner .der-banner .cont-columnas .columna{
        width: 33%;
    }
    .banner .der-banner .cont-columnas .columna img{
        width: 30%;
        padding-bottom: 10px;
    }
    .banner .der-banner .cont-columnas .columna p{
        color: #023B4F;
        font-size: 20px;
    }


@media (max-width:768px){
    .banner{
        display: block;
        align-items: center;
        justify-content: center;
    }
    .banner .izq-banner{
        display: block;
        padding:15px;
        text-align: center;
        width: 100%;
        height: 250px;
    }
    .banner .izq-banner .izq-banner-h1{
        width: 60%;
        height: 80px;
        color: #023B4F;
        font-size: 12px;
    }
    .banner .izq-banner img{
        width: 80%;
        height: 200px;
        transform: rotate(5deg);
    }
    .banner .der-banner{
        padding:10px;
        display: flex;
        width: 100%;
        display: block;
        text-align: center;
    }
    .banner .der-banner .der-banner-h1{
        width: 100%;
        height: 150px;
        color: #FD8F16;
        padding-top: 40px;
        align-items: center;
        margin: 0px auto;
        font-size: 12px;
    }
    .banner .der-banner .cont-columnas{
        width: 100%;
        display: flex;
    }
    .banner .der-banner .cont-columnas .columna{
        width: 33%;
    }
    .banner .der-banner .cont-columnas .columna img{
        width: 50%;
        padding-bottom: 10px;
    }
    .banner .der-banner .cont-columnas .columna p{
        color: #023B4F;
        font-size: 15px;
    }
}
</style>