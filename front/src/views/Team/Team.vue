<i18n src="./../../locales/general.yaml"></i18n>
<template>
  <div class="container">
    <section class="section">
      <h1 class="title">{{ $t('my-teams', language) }}</h1>
    </section>
  </div>
</template>

<script>
import { mapState } from 'vuex'
export default {
  computed: {
    ...mapState(['language'])
  }
}
</script>

<style>

</style>
