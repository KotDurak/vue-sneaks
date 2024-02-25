<script setup>

</script>

<template>
  <header class="flex justify-between border-b border-slate-300 px-10 py-8">
    <div class="flex items-center gap-4">
      <img src="/logo.png" alt="Logo" class="w-10"/>
      <div>
        <h2 class="text-xl font-bold uppercase">Vue sneaks</h2>
        <p class="text-slate-400">Desription</p>
      </div>
    </div>

    <ul class="flex items-center gap-10">
      <li class="flex items-center gap-3 cursor-pointer">
        <img src="/cart.svg" alt="cart">
        <b>1250 rub</b>
      </li>
      <li class="flex items-center gap-3 cursor-pointer">
        <img src="/heart.svg" alt="cart">
        <b>Bookmarks</b>
      </li>
      <li class="flex items-center gap-3 cursor-pointer">
        <img src="/profile.svg" alt="cart">
        <b>Profile</b>
      </li>
    </ul>
  </header>
</template>

<style scoped>

</style>