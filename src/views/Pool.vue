<template>
  <div>
    Pool id: {{ $route.params.id }}
  </div>
</template>

<script>
export default {
  beforeMount () {
    console.log(this.$route.params.id)
  }
}
</script>
