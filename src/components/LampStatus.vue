<template>
  <div>
    <p>Lamba Durumu : {{status}}</p>
    <button @click="openLamp">Lambayı aç</button>
    <hr>
  </div>
</template>
<script>
export default {
    data: function(){
        return {
            status: "Kapalı"
        }
    },
    methods:{
        openLamp() {
            this.status = "Açık"
        }
    }
}
</script>

