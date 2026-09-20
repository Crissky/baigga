[Documentação](https://getbootstrap.com/docs/4.4/components/carousel/)

<div id="reviewCarousel" class="carousel slide" data-ride="carousel">
    <!-- BOTÕES DA PARTE INFERIOR -->
    <div class="carousel-indicators">
        <li data-target="#reviewCarousel" data-slide-to="0" class="active"></li>
        <li data-target="#reviewCarousel" data-slide-to="1"></li>
        <li data-target="#reviewCarousel" data-slide-to="2"></li>
    </div>
    <!-- IMAGENS -->
    <div class="carousel-inner">
        <div class="carousel-item active">
            <a href="IMAGE-PATH-1">
                <img
                    src="IMAGE-PATH-1"
                    class="d-block w-100"
                    alt="Imagem 1">
            </a>
        </div>
        <div class="carousel-item">
            <a href="IMAGE-PATH-2">
                <img
                    src="IMAGE-PATH-2"
                    class="d-block w-100"
                    alt="Imagem 2">
            </a>
        </div>
        <div class="carousel-item">
            <a href="IMAGE-PATH-3">
                <img
                    src="IMAGE-PATH-3"
                    class="d-block w-100"
                    alt="Imagem 3">
            </a>
        </div>
    </div>
    <!-- BOTÕES DE AVANÇAR E RETORCEDER -->
    <a class="carousel-control-prev"
       href="#reviewCarousel"
       role="button"
       data-slide="prev">
        <span class="carousel-control-prev-icon"></span>
        <span class="sr-only">Anterior</span>
    </a>
    <a class="carousel-control-next"
       href="#reviewCarousel"
       role="button"
       data-slide="next">
        <span class="carousel-control-next-icon"></span>
        <span class="sr-only">Próxima</span>
    </a>
</div>


## AUMENTA A LEGIBILIDADE DOS BOTÕES DO CAROUSEL
```csv
.carousel-control-prev-icon,
.carousel-control-next-icon {
    width: 36px;
    height: 36px;
    background-color: rgba(0, 0, 0, 0.55);
    background-size: 45% 45%;
    border-radius: 50%;
}
```