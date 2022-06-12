<template>
  <ul>
    <li v-for="item in products" :key="item.id">
      {{ item.nama }} - {{ item.posisi }}
    </li>
  </ul>
</template>

<script>
  export default {
    name: 'App',
    data() {
      return {
        products: [
          {
            id: 1,
            nama: "Yeji",
            posisi: "leader"
          },
          {
            id: 2,
            nama: "Lia",
            posisi: "main vocal"
          },
          {
            id: 3,
            nama: "Chaeryong",
            posisi: "main dancer"
          },
          {
            id: 4,
            nama: "Ryujin",
            posisi: "main dancer"
          },
          {
            id: 5,
            nama: "Yuna",
            posisi: "maknae"
          }]
      };
    },
  };
  </script>

  <style>
    #app {
      font-family: Avenir, Helvetica, Arial, sans-serif;
      -webkit-font-smoothing: antialiased;
      -moz-osx-font-smoothing: grayscale;
      text-align: center;
      color: #2c3e50;
      margin-top: 60px;
    }
  </style>