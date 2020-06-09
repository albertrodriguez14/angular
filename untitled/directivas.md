# Directivas

las directivas  inician con la letra V  y seguido de nombre  ejemplo v-directiva

**v-for**

```text
<ul>
   <li v-for = ' messages in message'> 
   </ul>


  ---------------------------------------
  new Vue ({

    el: '#app',
    data:{
            message :[
               {nombre : 'aplica1'},
               {nombre : 'aplica2'},
               {nombre : 'aplica3'}
             ]

    }

  });
  ------------------------------------
```

\*\*\*\*

**v-model** 

\*\*\*\*

```text
<input type="text" v-model = "message">
```

\*\*\*\*

**v-if    /  v-else**

```text
 <div id="app">
               
   <ul>
    <input type="text" v-model = "message">
  <span  v-if="message.length > 2"  v-text ='message'></span> 
      <span v-else >escribe una cosa</span>
      </ul>

    </div>
    -----------------------------------------------
    new Vue ({

    el: '#app',
    data:{
            message : ' hola vue'

    }

  });
```

\*\*\*\*

**v-on:click** 

```text
<button class="btn btn-primary btn-md" @click="addnewtask">+</button>


 methods: {
          addnewtask: function () {
            this.task.push({
              nombre: this.newtask,
              completa: false,
            });
            this.newtask = "";
          },
```

```text
@click="messages.Completa = false"

 task: [
          { nombre: "mi z", Completa: true },
          { nombre: "mi 2", Completa: false },
          { nombre: "mi 3", Completa: true },
          { nombre: "mi 5", Completa: true },
```

**v-on:keyup**

```text
 <input  v-on:keyup.enter="addnewtask" 
  class="form-control" v-model="newtask" type="text" />
```

