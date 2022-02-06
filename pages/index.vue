<template>
  <Navigation></Navigation>
</template>

<script>
export default {
  head:{
    title:'Homepage'
  },
  layout:'homepage',
  created() {
    console.log('componnet is created')
  },
  mounted() {
    console.log('This is last lifecycle of app')
  },
}

</script>
