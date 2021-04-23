<template>
  
  <h1> this is a heading</h1>
  <p> now let's make a paragraph. Mon dieu!!</p>
  <p> Aller on essaye de mettre un peu de serieux avec Vue</p>
  <p> passage de nom: {{name}}</p>
  <p> Allez tourne tourne!!! {{counter}} </p>


</template>

<script>
export default {
  name: 'App',
  
   data(){
        return {
            counter: 0,
            name: "coucou mon petit oiseau!!"
        }
    },
    mounted(){
        setInterval(() =>{
            this.counter++
        },100)
    }


}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
