<script setup>
import ProductCard from '../components/ProductCard.vue'
const daftarProduk = [
 { id: 1, nama: 'Seragam Sekolah', harga: 175000, gambar:
'https://placehold.co/150' },
 { id: 2, nama: 'Buku Sekolah', harga: 135000, gambar:
'https://placehold.co/150' },
 { id: 3, nama: 'Tas Sekolah', harga: 120000, gambar:
'https://placehold.co/150' },
 { id: 4, nama: '', harga: 90000, gambar:
'https://placehold.co/150' },
]
</script>
<template>
 <main>
 <h1>Produk Kami</h1>
 <div class="grid">
 <ProductCard
 v-for="produk in daftarProduk"
 :key="produk.id"
 :nama="produk.nama"
 :harga="produk.harga"
 :gambar="produk.gambar"
 />
 </div>
 </main>
</template>
<style scoped>
.grid {
 display: flex;
 gap: 16px;
 flex-wrap: wrap;
}
</style>
