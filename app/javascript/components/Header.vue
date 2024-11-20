<template>
  <div class="header-container">
    <div class="header-left">
      <h2 class="logo">クラロワ屋</h2>
      
    </div>
    <div class="header-right">
      <ul class="header-lists">
        <li>新規登録</li>
        <li>ログイン</li>
        <li>ゲストログイン</li>
      </ul>
    </div>
  </div>
</template>

<script></script>
<style scoped>
li{
  list-style: none;
}

.header-container{
  width: 100%;
  height: 80px;
  background:linear-gradient(45deg,#0099FF 0%,#0099FF 50%,#FF3333 50%,#FF3333 100%);
  display: flex;
  justify-content: space-between;
}

.logo{
  color: white;
  padding:5px;
}

.header-lists{
  display: flex;
  margin-right: 10px;
}

.header-lists li{
  color: white;
  padding: 10px;
}
</style>
