<i18n src="./../../locales/general.yaml"></i18n>
<template>
  <div class="container">
    <section class="section">
      <h1 class="title"> {{ $t('space-committee', language) }} </h1>
    </section>
  </div>
</template>

<script>
import { mapState } from 'vuex'
export default {
  metaInfo () {
    return {
      title: this.$t('intro', this.language)
    }
  },
  computed: {
    ...mapState(['language'])
  }
}
</script>

<style>

</style>
