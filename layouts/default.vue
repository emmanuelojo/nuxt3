<template>
  <div>
    <header>
      <nav>
        <NuxtLink to="/">007</NuxtLink>
        <ul>
          <li>
            <NuxtLink to="/">Home</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/about">About</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/products">Products</NuxtLink>
          </li>
        </ul>
      </nav>
    </header>

    <div>
      <slot />
    </div>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped>
.router-link-exact-active {
  color: #12b488;
}
</style>
