<template>
  <div id="app">
    <!-- Boardコンポーネントの呼び出し -->
    <board />
  </div>
</template>

<script>
import Board from './components/Board.vue'

export default {
  name: 'App',
  components: {
    // コンポーネントに登録する
    Board
  }
}
</script>