<template>
  <div class="header-container">
    <div class="header-contents flex">
      <div class="header-left flex">
        <h2 class="logo">クラロワ屋</h2>
        <div class="tab-contents">
          <ul class="tab-lists flex">
            <RouterLink to="/"><li>HOME</li></RouterLink>
            <RouterLink to="/index"><li>デッキ一覧</li></RouterLink>
          </ul>
        </div>
      </div>
      <div class="header-right">
        <ul class="header-lists flex">
          <li>新規登録</li>
          <li>ログイン</li>
          <li>ゲストログイン</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script></script>
<style scoped>
li{
  list-style: none;
}

.flex{
  display: flex;
}

.header-container{
  width: 100%;
  height: 80px;
  background: #0099FF;
}

.header-contents{
  justify-content: space-between;
}

.logo{
  color: white;
  padding:5px;
}

.header-lists{
  margin-right: 10px;
}

.header-lists li{
  color: white;
  padding: 10px;
}

.tab-contents{
  background: #0099FF;
  justify-content: space-between;
}

.tab-lists{
  margin-right: 10px;
}

.tab-lists li{
  color: white;
  padding: 10px;
}
</style>
