<template>
  <div class="home">
    home
    <p> My name is {{ name }} and my age is {{ age }}</p>
  </div>
</template>

<script>
export default {
  name: 'Home',
  setup() {
    let name = 'junior'
    let age = 25

    return { name, age }
  }
}
</script>
