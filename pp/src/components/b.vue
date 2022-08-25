<template>
  <div>
    bbbbbbbbbb
    <div class='left'>左</div>
    <div class='center'>中</div>
     <div class='right'>右</div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
/* 圣杯布局 */
html,body{
  height:100%;
}
  .left{
    float:left;
    background:red;
    height:80%;
    width:100px;
  }
  .right{
    float:right;
    background:blue;
    height:80%;
    width:100px;
  }
  .center{
    background:yellow;
    overflow:hidden;
    height:100%
  }
  /* 圣杯布局2 */
  html,body{
  height:100%;
}
body{
  display:flex
}
.left{
  width:100px;
  height:80%;
  background:red
}
.right{
  flex:1;
  background:blue
}
</style>
