<template>
  <header>
    <h1>{{ $store.state.headerText }}</h1>
  </header>
</template>

<script>
export default {
  name: "TodoHeader",
}
</script>

<style lang="sass" scoped>
  h1
    color: #2f3b52
    font-weight: 900
    margin: 2.5rem 0 1.5rem

</style>