<template>
  <h1>This is a secret page.</h1>
</template>

<script>
  export default {
    middleware: 'auth'
  }
</script>