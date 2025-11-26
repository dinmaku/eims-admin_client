<template>
<router-view />
</template>


<script>
export default{
  name: 'App',
   mounted() {
    console.log("==== Checking VITE_API_URL ====");
    console.log(import.meta.env.VITE_API_URL);
  }
  }


</script>

<style>
#App {
  font-family:Verdana, Geneva, Tahoma, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}


</style>
