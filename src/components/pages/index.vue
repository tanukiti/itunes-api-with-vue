<template>
<section>
  <h1>hello world</h1>
  <item text="one"></item>

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
