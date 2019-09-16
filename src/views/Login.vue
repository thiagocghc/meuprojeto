import Vue from 'vue'

<template>


 <div>

<v-form>

    oi estou na página de login
</v-form>

<h1>Olá mundo!!</h1>

<input type="text" v-model="login"></input>

<v-btn @click="logar()" color="blue" outline>Logar</v-btn>
{{login}}

 </div>


</template>


<script>
export default{
    data (){
        return {
            login:"",
            senha:""
        }
    },
    methods: {
        logar(){
            if(this.login=="kkk"){
                console.log("OK");
             }
             else{
                console.log("ERROU"); 
             }
        }
    },
    create(){


    },

    mounted(){
        

    },

            

    }

</script>

<style>

</style>