<template>
     <p>{{ msg }}</p>
</template>

<script>
export default {
  name: 'Derp',
  props: {
    msg: String,
  }
}
</script>

<style scoped>
p{
text-align: center;
font-size: 36px;
color: red;}
</style>


