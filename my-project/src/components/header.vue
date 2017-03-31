<template lang="html">
      <header class="main-header">
        {{msg}}
      </header>
</template>

<script>
export default {
    data(){
      return {
        msg:"我是头部"
      }
    }
}
</script>

<style lang="css">
    .main-header{
      width: 100%;
      height: 30px;
      background-color: red;
    }
</style>
