<template>
  <div class="wrapper">
    <header>
      <p>商家列表</p>
    </header>
    <!--中心-->
    <ul class="business">
      <li onclick="location.href='businessInfo.html'">
        <div class="business-img">
          <img src="@/assets/img/jpg/饺子馆.jpg">
          <div class="business-img-quantity">3</div>
        </div>
        <div class="business-info">
          <h3>万家饺子（软件园E18店）</h3>
          <p>&#165;15起送 | &#165;3配送</p>
          <p>各种饺子炒菜</p>
        </div>
      </li>
      <li onclick="location.href='businessInfo.html'">
        <div class="business-img">
          <img src="@/assets/img/jpg/豆腐脑.jpg">
          <div class="business-img-quantity">2</div>
        </div>
        <div class="business-info">
          <h3>小锅饭豆腐馆（全运店）</h3>
          <p>&#165;15起送 | &#165;3配送</p>
          <p>特色美食</p>
        </div>
      </li>
      <li onclick="location.href='businessInfo.html'">
        <div class="business-img">
          <img src="@/assets/img/jpg/麦当劳.jpg">
          <div class="business-img-quantity">1</div>
        </div>
        <div class="business-info">
          <h3>麦当劳麦乐送（全运路店）</h3>
          <p>&#165;15起送 | &#165;3配送</p>
          <p>汉堡薯条</p>
        </div>
      </li>
      <li onclick="location.href='businessInfo.html'">
        <div class="business-img">
          <img src="@/assets/img/jpg/拌饭.jpg">
        </div>
        <div class="business-info">
          <h3>米村拌饭（浑南店）</h3>
          <p>&#165;15起送 | &#165;3配送</p>
          <p>各种炒菜拌饭</p>
        </div>
      </li>
      <li onclick="location.href='businessInfo.html'">
        <div class="business-img">
          <img src="@/assets/img/jpg/烧烤.jpg">
        </div>
        <div class="business-info">
          <h3>申记串道（中海康城店）</h3>
          <p>&#165;15起送 | &#165;3配送</p>
          <p>烤串炸串</p>
        </div>
      </li>
      <li onclick="location.href='businessInfo.html'">
        <div class="business-img">
          <img src="@/assets/img/jpg/排骨.jpg">
        </div>
        <div class="business-info">
          <h3>半亩良田排骨米饭</h3>
          <p>&#165;15起送 | &#165;3配送</p>
          <p>排骨米饭套餐</p>
        </div>
      </li>
      <li onclick="location.href='businessInfo.html'">
        <div class="business-img">
          <img src="@/assets/img/jpg/果汁.jpg">
        </div>
        <div class="business-info">
          <h3>茶兮鲜果饮品（国际软件园店）</h3>
          <p>&#165;15起送 | &#165;3配送</p>
          <p>甜品饮品</p>
        </div>
      </li>
      <li onclick="location.href='businessInfo.html'">
        <div class="business-img">
          <img src="@/assets/img/jpg/水果捞.jpg">
        </div>
        <div class="business-info">
          <h3>唯一水果捞（软件园E18店）</h3>
          <p>&#165;15起送 | &#165;3配送</p>
          <p>新鲜水果</p>
        </div>
      </li>
      <li onclick="location.href='businessInfo.html'">
        <div class="business-img">
          <img src="@/assets/img/png/春饼.png">
        </div>
        <div class="business-info">
          <h3>满园春饼（全运路店）</h3>
          <p>&#165;15起送 | &#165;3配送</p>
          <p>各种春饼</p>
        </div>
      </li>
    </ul>
    <bottom></bottom>
  </div>
</template>

<script>
export default {
  name: "businessList"
}
</script>

<style scoped>
.wrapper{
  width: 100%;
  height: 100%;
}
.wrapper header{
  width: 100%;
  height: 12vw;
  background-color: #0097FF;
  color: #fff;
  font-size: 4.8vw;
  position: fixed;
  left: 0;
  top: 0;
  z-index: 1000;

  display: flex;
  justify-content: center;
  align-items: center;
}
.wrapper .business{
  width: 100%;
  margin-top: 12vw;
  margin-bottom: 14vw;
}
.wrapper .business li{
  width: 100%;
  box-sizing: border-box;
  padding: 2.5vw;
  border-bottom: solid 1px #DDD;
  user-select: none;
  cursor: pointer;
  display: flex;
  align-items: center;
}
.wrapper .business li .business-img{
  position: relative;
}
.wrapper .business li .business-img img{
  width: 20vw;
  height: 20vw;
}
.wrapper .business li .business-img .business-img-quantity{
  width: 5vw;
  height: 5vw;
  background-color: red;
  color: #fff;
  font-size: 3.6vw;
  border-radius: 2.5vw;

  display: flex;
  justify-content: center;
  align-items: center;

  position: absolute;
  right: -1.5vw;
  top: -1.5vw;
}
.wrapper .business li .business-info{
  margin-left: 3vw;
}
.wrapper .business li .business-info h3{
  font-size: 3.8vw;
  color: #888;
  margin-top: 2vw;
}

</style>
