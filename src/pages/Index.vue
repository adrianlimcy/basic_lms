<template>
  <q-page class="flex justify-center">
    <div class="q-pa-md row items-start q-gutter-md">
      <q-card class="my-card">
        <img src="https://cdn.quasar.dev/img/mountains.jpg">

        <q-card-section>
          <div class="text-h6">Pitch Book</div>
          <div class="text-subtitle2">What our products can do</div>
        </q-card-section>

        <q-card-section class="q-pt-none">
          {{lorem}}
        </q-card-section>
      </q-card>

      <q-card class="my-card">
        <img src="https://cdn.quasar.dev/img/mountains.jpg">

        <q-card-section>
          <div class="text-h6">Training Page</div>
          <div class="text-subtitle2">Learn our products</div>
        </q-card-section>

        <q-card-section class="q-pt-none">
          {{lorem}}
        </q-card-section>
        <div class="q-pa-sm">
          <q-btn to="/lessons" color="primary" label="Lessons" />
        </div>
      </q-card>

      <q-card class="my-card">
        <img src="https://cdn.quasar.dev/img/mountains.jpg">

        <q-card-section>
          <div class="text-h6">Quiz Time</div>
          <div class="text-subtitle2">Test your knowledge</div>
        </q-card-section>

        <q-card-section class="q-pt-none">
          {{lorem}}
        </q-card-section>
        <div class="q-pa-sm">
          <q-btn to="/quizzes" color="primary" label="Quizzes" />
        </div>
      </q-card>
    </div>
  </q-page>
</template>

<script>
export default {
  name: 'PageIndex',
  data () {
    return {
      lorem: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.'
    }
  }
}
</script>

<style lang="sass" scoped>
.my-card
  width: 100%
  max-width: 250px
</style>
