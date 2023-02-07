<template>
  <div class="row">

<div class="col-">
<TopMenu/>
<Page_title pageTitle="sefse"/>

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
    name: "lunch",
    components: { Page_title, TopMenu }
}
</script>

<style lang="scss" scoped>

</style>