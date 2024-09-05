* <input type="text" v-model="message"> = sirve para poder recibir el mensaje de afuera, y podemos modificar desde la pc
### estructura basica para Vue
<div id="app">
    <h1> {{message}} </h1>
</div>
<script src="vue.js"> </script>
<script>
    var vm = new Vue({
        el:"#app", 
        data:{
            message: "hola mundo"
        }
    });
</script>

### conceptos

* one way binding = nos permite la sincronizacion de nuestra instancia con el dom
* two way binding = del exterior con la propiedad y viceversa