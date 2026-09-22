<template>
  <div class="landing">

    <section class="hero bg-yellow-100 p-[100px] flex flex-col items-center text-center gap-[18px]">
      <h1 class="text-[58pt] text-center text-yellow-800 font-serif">hello welcome in sunflower online shop</h1>
      <p class="text-[20pt] text-yellow-800 font-serif">mari mari menghamburkan uang</p>

      <router-link
        to="/product"
        class="mt-10 mb-10 inline-block rounded-full bg-white px-8 py-3 text-lg font-serif text-yellow-800 transition duration-150 hover:bg-lime-50 active:scale-95 md:text-xl"> yukss </router-link>
    

      <div class="flex justify-center">
        <video controls width="480" muted loop>
          <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4" />
        </video>
      </div>
    </section>

    <main>
      <section class="cow grid grid-cols-1 md:grid-cols-3 gap-6 p-10">
        <div class="card ail">
          <span class="card-icon">💵</span>
          <h3>harga yang tercantum buat yang mampu mampu aja sie</h3>
          </div>
        <div class="card oi">
          <span class="card-icon">✨</span>
          <h3>produk yang kita jual dijamin berkualitas tinggi dan terpercaya</h3>
        </div>
        <div class="card lai">
          <span class="card-icon">🤏🏻</span>
          <h3>produk yang dibeli bisa diambil di sekolah, jangan manja</h3>
        </div>
      </section>
    </main>

  </div>
</template>

<script setup>
</script>

<style scoped>
.card {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  gap: 10px;
  padding: 24px;
  border-radius: 12px;
  background: #fff;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.08);
}

.card-icon {
  font-size: 2rem;
}

video {
  margin-top: 16px;
  border-radius: 10px;
  display: inline-block;
}
</style>