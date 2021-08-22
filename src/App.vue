<template>
  <v-app>
    <v-main>
      <ChatPage/>
    </v-main>
  </v-app>
</template>

<script>
import ChatPage from './components/ChatPage'

export default {
  name: 'App',
  components: {
    ChatPage
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e5f;
  margin-top: 60px;
}
</style>
