<template>
<section>
  <h1>{{text}}</h1>
</section>
</template>

<script>
export default {
    props: ["text"],
    data(){
        return {
            text: ""
        }
    }
}
</script>

<style>
    p {
        color: blue;
        float: right;
        font-size: 18px;
    }
    h1 {
        color: brown;
    }
</style>
