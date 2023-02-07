<template>
  <div class="row">

<div class="col-">
<TopMenu/>
<Page_title pageTitle="abc"/>

<p>

    <button type="button" class="btn btn-primary">Primary</button>
</p>


</div>

  </div>

</template>

<script>
import Page_title from '../components/Page_title.vue';

    export default {
    layout: "HomePage",
    name: "order",
    components: { Page_title }
}
</script>

<style lang="scss" scoped>

</style>