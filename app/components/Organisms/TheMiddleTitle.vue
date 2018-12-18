<template>
  <div class="middle">
    <KaigoFirstChat class="left-component"/>
    <KaigoAnswerSample class="right-component"/>
  </div>
</template>

<script>
import KaigoFirstChat from '../Molecules/KaigoFirstChat.vue'
import KaigoAnswerSample from '../Molecules/KaigoAnswerSample.vue'

export default {
  components: {
    KaigoFirstChat,
    KaigoAnswerSample
  }
}
</script>

<style>
.middle {
  display: flex;
  margin: 0 auto;
  box-sizing: inherit;
  background-repeat: no-repeat;
}
.left-component {
  text-align: center;
  width: 40%;
  margin: 0 2% 0 10%;
}
.right-component {
  text-align: center;
  width: 40%;
  margin: 0;
}
</style>
