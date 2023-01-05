<template>
  <div class="message-container">
    <p>{{ this.msg }}</p>
  </div>
</template>

<script>
export default {
  name: "Mensagem",
  props: {
    msg: String,
  },
};
</script>

<style scoped>
.message-container {
  color: red;
  background-color: #cce5fc;
  border: 2px solid #b8daff;
  border-radius: 5px;
  padding: 10px;
  max-width: 400px;
  margin: 30px auto;
}
</style>
