<template>
  <div>
    <p>Server Details: {{ status}}</p>
    <hr>
    <button @click = "changeStatus">Change Status</button>

  </div>
</template>

<script>
export default {
  name: 'ServerDetails',
  data: function () {
    return {
      status: 'critical'
    }
  },
  methods: {
    changeStatus() {
      this.status = 'Normal';
    }
  }
}

</script>

<style>
p{
  width: 50%;
  text-align: left;
  padding-left: 1rem;
}
</style>
