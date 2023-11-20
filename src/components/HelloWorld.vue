<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      자신이 소장하고 있는 소장품을 BidBird를 통해 경매를 진행해 보세요.<br>
      BidBird 서비스는
      <a href="http://gorgeouswrks.com" target="_blank" rel="noopener">Gorgeous팀</a>이 만들었습니다..
    </p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
