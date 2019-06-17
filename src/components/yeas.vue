<template>
  <div>
    <input v-model.number="idade" type="number">
    <button type="submit" @click="whaiYear(idade)">Enviar</button>
  </div>
</template>

<script>
export default {
  methods: {
    whaiYear(idade) {
      if (idade < 18) {
        alert("Você é menor de idade");
      } else {
        alert("Você é maior de idade");
      }
    }
  }
};
</script>

