<!--
 * @Descripttion: 
 * @version: 
 * @Author: RoyalKnight
 * @Date: 2020-09-28 15:29:31
 * @LastEditors: RoyalKnight
 * @LastEditTime: 2020-10-02 20:51:10
-->
<template>
      <div class="mc_middle">
          <slot></slot>
      </div>
</template>

<script>
import setting from '../js/setting'
export default {
  name: "mc-middle",
  mixins:[setting],
  data:function(){
      return{
          
      }
  },
  mounted: function () {
    
  },
};
</script>
<style scoped>
.mc_middle{
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
}
</style>