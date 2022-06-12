<template>
  <Header />
</template>

<script>
  import Header from "@/components/Header.vue";
  export default {
    name: 'App',
    itzy: [{
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
      }],
    components: {
      Header,
    },
  };
  </script>

  <style>
  </style>