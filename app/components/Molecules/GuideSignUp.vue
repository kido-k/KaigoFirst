<template>
  <section>
    <div class="guide">
      <KaigoFirstLabel class="label"/>
      <SignUpButton class="button"/>
    </div>
  </section>
</template>

<style scoped>
.guide {
  text-align: center;
  margin: 40px 0 0 0;
}
.button {
  margin: 25px 0 0 0;
}
</style>


<script>
import KaigoFirstLabel from '~/components/atoms/KaigoFirstLabel.vue'
import SignUpButton from '~/components/atoms/SignUpButton.vue'

export default {
  components: {
    KaigoFirstLabel,
    SignUpButton
  }
}
</script>
