<template>
  <div class="melon">
    <h1>{{ msg }}</h1>
    <p>
      In the beginning, there were melons. And over 150 years since the beginning of the capitalist society,
      everything changed. Through the power of blockchain, the humble farmers of Yubari, Hokkaido, created a
      revolutionary payment system backed by the world's most expensive fruit.
      It's not just a cryptocurrency -- it's a state of mind.
    </p>
    <p>
      メロンコインはフルーツの仮想通貨です。
    </p>
    <h3>Essential Links</h3>
    <ul>
      <li><a href="https://twitter.com/meloncointoken" target="_blank">Twitter</a></li>
      <li><a href="assets/meloncoin-whitepaper-v1.pdf" target="_blank">Whitepaper</a></li>
      <li><a href="https://docs.google.com/forms/d/e/1FAIpQLSd8O1BB_VzD9ymLZ1rhUBT6ZE7YhIrZWnGrtwLf-rbTBqXfJg/viewform?usp=sf_link" target="_blank">Mailing List</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'MelonCoin',
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
