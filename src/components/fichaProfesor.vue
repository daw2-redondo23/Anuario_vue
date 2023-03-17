<template>
    <div class="col-2 offset-1 px-4">
      <div class="card carta shadow">
        <img class="cardProfesor" :src='"/public/img/"+persona.photo' :alt='persona.nombre'>
        <p class="text-center pt-3">{{persona.nombre}}</p>
      </div>
    </div>
</template>

<script>
export default {
    name: 'Card',
    //Props es para recibir variables, en este caso le dicimos que va a recibir una variable.
    //Recibira la array de ListaAlumnos y se guardara. Tenemos que decirle que funcion es
    props: {
        persona: Object
    }
}
</script>

<style>

</style>