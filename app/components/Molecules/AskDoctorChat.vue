<template>
  <section>
    <div class="middle-title">
      <KaigoChatTitle/>
      <KaigoChatLabel class="label"/>
      <MidlePicture/>
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
import KaigoChatTitle from '~/components/atoms/KaigoChatTitle.vue'
import KaigoChatLabel from '~/components/atoms/KaigoChatLabel.vue'
import MidlePicture from '~/components/atoms/AskDoctorMiddlePicture1.vue'

export default {
  components: {
    KaigoChatTitle,
    KaigoChatLabel,
    MidlePicture
  }
}
</script>
