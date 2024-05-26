<template>
  <q-header elevated class="bg-primary text-white">
    <q-toolbar>
      <q-btn
        flat
        round
        dense
        icon="menu"
        aria-label="Menu"
        @click="onMenuClick"
      />

      <q-toolbar-title>
        <q-avatar square>
          <img
            src="https://th.bing.com/th/id/OIP.WoR-3lsNWfbEuhtFnTkO7wHaE-?w=231&h=180&c=7&r=0&o=5&dpr=1.3&pid=1.7"
            alt="Logo"
          />
        </q-avatar>
        <span class="q-ml-sm">FAUZI COMPUTECH</span>
      </q-toolbar-title>

      <q-btn flat round dense icon="home" aria-label="Home">
        <q-tooltip content-class="bg-primary text-white">Home</q-tooltip>
      </q-btn>
      <q-btn flat round dense icon="shopping_cart" aria-label="Produk">
        <q-tooltip content-class="bg-primary text-white">Produk</q-tooltip>
      </q-btn>
      <q-btn flat round dense icon="contacts" aria-label="Kontak">
        <q-tooltip content-class="bg-primary text-white">Kontak</q-tooltip>
      </q-btn>

      <q-space />

      <q-btn flat round dense icon="account_circle" aria-label="Akun">
        <q-tooltip content-class="bg-primary text-white">Akun</q-tooltip>
      </q-btn>
      <q-btn flat round dense icon="shopping_cart" aria-label="Keranjang">
        <q-tooltip content-class="bg-primary text-white">Keranjang</q-tooltip>
      </q-btn>
    </q-toolbar>
  </q-header>
</template>

<script>
export default {
  name: "Navbar",
  methods: {
    onMenuClick() {
      // Handle menu click
    },
  },
};
</script>

<style scoped>
.q-toolbar-title {
  display: flex;
  align-items: center;
}

.q-toolbar-title img {
  height: 40px;
}

.q-btn {
  margin-left: 10px;
}
</style>
