<template>
  <div class="container">
    <NuxtLayout name="error">
      <template #header>
        <h2>Page Not Found !</h2>
      </template>
      <template #redirectEl>
        <NuxtLink to="/">Go Back</NuxtLink>
      </template>
    </NuxtLayout>
  </div>
</template>
<style>
.container {
  text-align: center;
  margin-top: 5rem;
}
</style>