<template>
<div>

 
  <div>
      <NavBar />

     
  </div>
  <!-- <div style="margin-top:137px;">

 <Table />
  </div> -->


  <div>
    <Table1/>
  </div>

   <Login/>
  </div>
</template>

<script>
import Login from './components/Login.vue';
import NavBar from "./components/NavBar.vue";
// import Table from "./components/Table.vue";
import Table1 from "./components/Table1.vue";
export default {
  name: 'App',
  components: {
  NavBar,
  // Table,
  Table1,
    Login
    
  
  }
}
</script>

<style>

</style>
