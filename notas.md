* message: "hola" = para imprimir mensajes
### estructura basica para Vue
<body>
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
</body> 

### conceptos
* binding = union entre las propiedades de nuestra instancia y el DOM