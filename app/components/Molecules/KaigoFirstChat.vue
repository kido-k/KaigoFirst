<template>
  <section>
    <div class="middle-title">
      <KaigoChatTitle/>
      <KaigoChatLabel class="label"/>
      <KaigoChatPicture/>
    </div>
  </section>
</template>

<style scoped>
.middle-title {
  display: inline-block;
  background-repeat: no-repeat;
}
.label {
  margin: 20px 0 0 0;
}
</style>


<script>
import KaigoChatTitle from '~/components/Atoms/KaigoChatTitle.vue'
import KaigoChatLabel from '~/components/Atoms/KaigoChatLabel.vue'
import KaigoChatPicture from '~/components/Atoms/KaigoChatPicture.vue'

export default {
  components: {
    KaigoChatTitle,
    KaigoChatLabel,
    KaigoChatPicture
  }
}
</script>
