<template>
  <footer>
    <!-- データを表示させます。-->
    <h1>{{title}}</h1>
    <p>{{subTitle}}</p>
    <p>{{addr}}</p>
    <p>{{copyright}}</p>
  </footer>
</template>

<script>
export default {
  //Vue インスタンスのためのデータオブジェクトです
  data(){
    return{
      title: "キャスレーコンサルティング株式会社",
      subTitle: "A \"Creating Shared Value\" company.",
      addr: "〒150-6031 東京都渋谷区恵比寿 4-20-3 恵比寿ガーデンプレイスタワー31階",
      copyright: "Casley Consulting Inc. All rights reserved."
    }
  }
}
</script>

<style>
footer{
  background-color: #c9c9c9;
  text-align: center;
  position:absolute;
  width:100%;
  bottom:0;
  overflow:hidden;
}
h1{
  color: #013892;
  margin: 0;
}
p{
  color:#000;
  margin: 0;
}
</style>
