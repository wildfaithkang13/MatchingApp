<template>
  <header>
    <!-- データを表示させます。-->
    <h1>{{title}}</h1>
    <p>{{subTitle}}</p>
  </header>
</template>

<script>
export default {
//Vue インスタンスのためのデータオブジェクトです
  data(){
    return{
      title: "ゲイのためのマッチングアプリ",
      subTitle: "Let's make a wonderful world!"
    }
  }
}
</script>

<style>
header{
  background-color: #f6f7f9;
  text-align: center;
  padding: 10px;
}
h1{
  color: #013892;
  margin: 0;
}
p{
  color:#999;
  margin: 0;
}
</style>
