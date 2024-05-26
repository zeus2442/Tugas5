<template>
    <q-footer class="bg-primary text-white q-pa-md">
      <div class="row items-center justify-between q-mb-md">
        <div class="col-auto">
          <q-avatar square size="56px">
            <img src="https://th.bing.com/th/id/OIP.WoR-3lsNWfbEuhtFnTkO7wHaE-?w=231&h=180&c=7&r=0&o=5&dpr=1.3&pid=1.7" alt="Logo">
          </q-avatar>
        </div>
        <div class="col-auto">
          <div class="text-h6">Fauzi Computech</div>
          <div class="text-subtitle2">Jl. Pasir Putih , Pekanbaru</div>
          <div class="text-caption">Email: @Fauzi_Computech | Telepon: 0812-3456-7890</div>
        </div>
        <div class="col-auto">
          <q-btn flat round dense icon="facebook" @click="goTo('https://facebook.com')" class="text-white">
            <q-tooltip content-class="bg-primary text-white">Facebook</q-tooltip>
          </q-btn>
          <q-btn flat round dense icon="twitter" @click="goTo('https://twitter.com')" class="text-white">
            <q-tooltip content-class="bg-primary text-white">Twitter</q-tooltip>
          </q-btn>
          <q-btn flat round dense icon="instagram" @click="goTo('https://instagram.com')" class="text-white">
            <q-tooltip content-class="bg-primary text-white">Instagram</q-tooltip>
          </q-btn>
        </div>
      </div>
      <div class="text-center q-pt-md">
        &copy; 2024 Toko Online Saya
      </div>
    </q-footer>
  </template>
  
  <script>
  export default {
    name: 'Footer',
    methods: {
      goTo(url) {
        window.open(url, '_blank')
      }
    }
  }
  </script>
  
  <style scoped>
  .q-footer {
    border-top: 1px solid rgba(255, 255, 255, 0.2);
  }
  .row {
    display: flex;
    flex-wrap: wrap;
  }
  .col-auto {
    flex: 0 0 auto;
  }
  </style>
  