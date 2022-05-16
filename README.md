<!-- CAMBIOS EN TITTLES -->

index.html : Cambio de titulo
contacto.html :Cambio de titulo
mayoristas : cambio de titulo
shatoosh.html : cambio de titulo


<!-- extend mixins y maps -->

° Agregue un extend en un parrafo y combine con una imagen

.p-viyela {
    font-size: 20px;
    padding-left: 10px; 
    margin: 0 auto;
                    }
  
  .imgviyela {
     @extend .p-viyela;
    width: 350px;
    border: solid;
    border-radius: 10px;
    margin: 30px; }

<!-- MAPS -->

°Quise agregar un maps para cambiar los colores de mis redes sociales, por ahora esta instagram solo


$redes: (
    twitter: #339be0,
    facebook: #0026a2,
    instragram: #c000f6,  
);

@each $red, $color in $redes {
        .red-#{$red}{
        }
}


<!-- MIXIN -->

° Agregue un mixin a una imagen con los siguientes valores :

@mixin size{
    width: 350px;
    margin: 30px;
    border-radius: 10px;
    }

.imgsarga{
    @include size;
}