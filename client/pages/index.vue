<template>
  <div class="container">
 <div class="row">
 
   <div class="col-12">
    <Hifive_logoa/>
    <TopMenu/>
   <h1>Welcome To The First Tutorial</h1>

     <p>To dynamically import a component, also known as lazy loading a component, all you need to do is add the Lazy prefix in your templates. Using the lazy prefix you can also dynamically import a component when an event is triggered.</p>
   </div>
   <button type="button" class="btn btn-primary">Primary</button>
 </div>
 
  </div>
 </template>

<script>
import Hifive_logoa from '../components/Hifive_logoa.vue';
import TopMenu from '../components/TopMenu.vue';



export default {
    layout: "HomePage",
    components: { Hifive_logoa, TopMenu }
}


</script>




