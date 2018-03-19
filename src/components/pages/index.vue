<template>
<section>
  <h1>Itunes 検索</h1>
  <item text="aho"></item>
  <item msg="hoge"></item>
</section>
</template>

<script>
import Item from "../modules/item.vue"
export default {
    components: {
        Item
    },
    created() {
        console.log("created!")
    },
    mounted() {
        console.log("mounted!")
    }
}
</script>

<style>
  h1 {
    color: blueviolet;
  }
</style>
