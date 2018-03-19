<template>
<section>
  <h1>{{text}}</h1>
  <p>{{msg}}</p>
</section>
</template>

<script>
export default {
    props: ["text", "msg"],
    data(){
        return {
            text: "",
            msg: ""
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
