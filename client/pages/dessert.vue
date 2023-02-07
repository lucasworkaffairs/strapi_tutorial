<template>
  <div class="row">

<div class="col-">
<TopMenu/>
<Page_title pageTitle="selifghneilsnfgiv"/>

<p>

    <button type="button" class="btn btn-primary">Primary</button>
</p>


</div>

  </div>


</template>

<script>
import Page_title from '../components/Page_title.vue';
import TopMenu from '../components/TopMenu.vue';

    export default {
    layout: "HomePage",
    name: "dessert",
    components: { Page_title, TopMenu }
}
</script>

<style lang="scss" scoped>

</style>