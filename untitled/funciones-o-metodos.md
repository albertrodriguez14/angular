# pro. calculadas o métodos

```text
methods: {

add : function(){

code here

}

},

```

```text
 computed: {


        completedTasks: function () {
          console.log("trigger completos");
          return this.task.filter(function (task) {

            return task.tarea;


          }).length;

        },
        incompletedTasks: function () {
          console.log("trigger incompletos");
          return this.task.filter(function (task) {

            return !task.tarea;


          }).length;

        },


      }
```

la diferencias es que en los methods se utiliza cada instante cuando se escribe cada palabras en el input , y la computada solo se utiliza cuando  se actualiza el evento.

