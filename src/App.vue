<template>
  <div id="app" class="principal">
    <span>{{ titulo }}</span>
    <entrada />
  </div>
</template>

<script>
import Entrada from "@/views/Entrada.vue";

export default {
  components: { Entrada },
  data() {
    return {
      titulo: "Entradas"
    }
  }
};
</script>

<style>
html {
  font-size: 65.5% !important;
}

.principal {
  background-color: #a21010;
  padding: 10px;
  color: white;
  border-radius: 5px;
  width: 400px;
  font-size: 3rem;
  text-align: center;
}

a {
  text-decoration: none;
}

button {
  background-color: #553f75;
  color: white;
  font-size: 2.4rem;
  font-weight: bold;
  border-style: none;
  border-radius: 5px;
  padding: 3px 10px;
  margin: 3px 5px;
  min-width: 35px;
  cursor: pointer;
}
</style>
