<template>
  <main>
    <h1>Home page</h1>
    <section class="red">test</section>
    <NuxtLink to="/about"> About </NuxtLink>
  </main>
</template>

<script>
export default {
  name: 'IndexPage',
};
</script>

<style>
.red {
  height: 2000px;
  background-color: red;
}
</style>
