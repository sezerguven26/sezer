<template>
<div>
    <lamp-status v-for="lamp in 5" :key="lamp"></lamp-status>

</div>
</template>

<script>
import LampStatus from './LampStatus'
  export default {
    components: {
        "lamp-status" : LampStatus
    }
  };
</script>

<style>
</style>
