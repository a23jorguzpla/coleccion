<template>
  <div>
    <nav>
      <NuxtLink to="/">Home</NuxtLink> |
      <NuxtLink to="/search">Search</NuxtLink> |
      <NuxtLink to="/favorites">Favorites</NuxtLink> |
      <NuxtLink to="/item/1">Detail</NuxtLink>
    </nav>

    <main>
      <slot />
    </main>
  </div>
</template>