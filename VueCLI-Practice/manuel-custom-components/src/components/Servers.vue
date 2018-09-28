<template>
  <ul>
    <li>Server #1</li>
    <li>Server #2</li>
    <li>Server #3</li>
    <li>Server #4</li>
    <li>Server #5</li>
  </ul>
</template>

<script>
export default {
  name: 'Servers'
}
</script>

<style scoped>
  ul{
    display: flex;
    flex-direction: column;
    width: 50%;
  }
  ul li {
    list-style-type: none;
    border: solid #000 2px;
    text-align: left;
  }
</style>

