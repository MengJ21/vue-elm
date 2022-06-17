<template>
  <div class="wrapper">
    <ul class="footer">
      <li onclick="location.href='index.html'">
        <i><font-awesome-icon :icon="['fa', 'home']"></font-awesome-icon></i>
        <p>首页</p>
      </li>
      <li>
        <i><font-awesome-icon :icon="['fa', 'compass']"></font-awesome-icon></i>
        <p>发现</p>
      </li>
      <li onclick="location.href='orderList.html'">
        <i><font-awesome-icon :icon="['fa', 'file-text']"></font-awesome-icon></i>
        <p>订单</p>
      </li>
      <li>
        <i><font-awesome-icon :icon="['fa', 'fa-user']"></font-awesome-icon></i>
        <p>我的</p>
      </li>
    </ul>
  </div>
</template>

<script>
import '/src/css/reset.css'
import '@fortawesome/fontawesome-free'
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/****************** 底部菜单部分 ******************/
.wrapper{
  width: 100%;
  height: 0vw;
}
.wrapper .footer{
  width: 100%;
  height: 14vw;
  border-top: solid 1px #DDD;
  background-color: #fff;

  position: fixed;
  left: 0;
  bottom: 0;

  display: flex;
  justify-content: space-around;
  align-items: center; }
.wrapper .footer li{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;

  color: #999;
  user-select: none;
  cursor: pointer; }
.wrapper .footer li p{
  font-size: 2.8vw; }
.wrapper .footer li i{
  font-size: 5vw; }

</style>
