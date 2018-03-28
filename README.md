# hello-world
primer repositorio

var coleccion = [];

class mes {
  constructor(nombre, dias, estacion)
   {
    this.nombre = nombre;
    this.dias = dias;
    this.estacion = estacion;
   }
}

function nuevoMes(){
    var nombre = document.getElementById('txtnombre');
    var dias = document.getElementById('txtdias');
    var estacion = document.getElementById('txtestacion');


    coleccion.push(new mes(nombre.value, dias.value, estacion.value));
    //coleccion.push(new mes('Febrero', 28, 'invierno'));
    console.log(coleccion);
  }

var h = document.getElementById('btnAceptar');
h.addEventListener('click', nuevoMes);
