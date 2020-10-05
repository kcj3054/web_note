<template>
    <div class="header">     
      <img src="../assets/logo.png">
      <p>Vue.JS Sticky Notes</p>
      <button class="add-btn" @click.prevent="openEditor"><i class="fas fa-plus"></i></button>    
    </div>
</template>

<script>
    export default {
       methods:{
          openEditor: function(){
            this.$emit('openEditor');
          }
        }
    }
</script>