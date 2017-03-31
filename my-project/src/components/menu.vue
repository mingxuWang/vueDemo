<template lang="html">
    <div class="menu">
        <template v-for = "menu in menuList">
            <router-link :to="menu.id">
              <span>{{menu.name}}</span>
            </router-link>
        </template>
    </div>
</template>

<script>
export default {
  data(){
    return {
      menuList:[
        {
          "name":"测试一",
          "id":"home"
        },
        {
          "name":"测试二",
          "id":"myMarket"
        },
        {
          "name":"测试三",
          "id":"my"
        },
      ]
    }
  }
}
</script>

<style lang="css">
    .menu{
      position: fixed;
      bottom: 0;
      left: 0;
      width: 100%;
      height: 30px;
      background-color: green;
    }
</style>
