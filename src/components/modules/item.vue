<template>
  <h1>{{text}}</h1>
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