<template>
  <b-button to="/detail">{{ text }}</b-button>
</template>

<script>
    export default {
        name: 'DetailButton',
        props : {
            text : {
                type: String,
                default: 'View Detail'
            }
        }
    }
</script>

<style scoped>

</style>
