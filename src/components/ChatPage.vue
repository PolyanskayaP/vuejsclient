<template>
  <v-container>
    <div id="example-1">
      <button v-on:click="counter += 1">+1</button>
      <p>Кнопка выше была нажата {{ counter }} раз</p>
    </div>
  </v-container>
</template>

<script>
//export default {
 // name: 'HelloWorld',
 // props: {
 //   msg: String
 // }
//}

export default {
  // Модель данных страницы
  data: () => {
    return {
      counter: 0,
      username: '',
      message: '',
      // messages: [
      //   { "UserName":"RusAl","MessageText":"Privet na sto let!!!","TimeStamp":"2021-03-05T18:23:10.932973Z"},
      //]
      messages: [],
      intervalCtx: null,
      lastMsgID: 0,
    }
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
