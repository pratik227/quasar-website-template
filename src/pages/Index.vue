<template>
  <q-page>
<!--    <section style="min-height: 30vh;" class="flex text-white flex-center layout_bg">-->
<!--      <div style="position: relative">-->
<!--        <div class="text-h2">-->
<!--          <div class="text-weight-bold">Quasar</div>-->
<!--          Template-->
<!--        </div>-->
<!--      </div>-->
<!--    </section>-->
    <section style="min-height: 30vh;">
      <div class="q-pa-none">
        <q-parallax :height="250" :speed="0.5">
          <template v-slot:media>
            <img src="../statics/bicycle.jpg" style="object-fit: cover;">
          </template>

          <div class="text-h2 text-white">
            <div class="text-weight-bold">Quasar</div>
            Template
          </div>
        </q-parallax>
      </div>
    </section>
    <section>
      <div class="row justify-center q-col-gutter-lg q-pa-lg">
        <q-card class="col-12 col-md-5 no-shadow">
          <q-card-section class="row ">
            <div class="col-12 text-h6 text-center">
              <q-icon name="important_devices" class=" q-mr-md" style="font-size: 38px;"></q-icon>
              Our Title
            </div>
          </q-card-section>
          <q-card-section class="text-left">
            Your full focus is on your App's content rather than all other boilerplating stuff around it (build system,
            layout, and much more). You'll be spending time only on what matters, which is your product. Quasar greatly
            increases your
            productivity.
          </q-card-section>
        </q-card>
        <q-card class="col-12 col-md-5  no-shadow">
          <q-card-section class="row ">
            <div class="col-12 text-h6 text-center">
              <q-icon name="important_devices" class=" q-mr-md" style="font-size: 38px;"></q-icon>
              Our Title
            </div>
          </q-card-section>
          <q-card-section class="text-left">
            Your full focus is on your App's content rather than all other boilerplating stuff around it (build system,
            layout, and much more). You'll be spending time only on what matters, which is your product. Quasar greatly
            increases your
            productivity.
          </q-card-section>
        </q-card>
        <q-card class="col-12 col-md-5 no-shadow">
          <q-card-section class="row ">
            <div class="col-12 text-h6 text-center">
              <q-icon name="important_devices" class=" q-mr-md" style="font-size: 38px;"></q-icon>
              Our Title
            </div>
          </q-card-section>
          <q-card-section class="text-left">
            Your full focus is on your App's content rather than all other boilerplating stuff around it (build system,
            layout, and much more). You'll be spending time only on what matters, which is your product. Quasar greatly
            increases your
            productivity.
          </q-card-section>
        </q-card>
        <q-card class="col-12 col-md-5 no-shadow">
          <q-card-section class="row ">
            <div class="col-12 text-h6 text-center">
              <q-icon name="important_devices" class=" q-mr-md" style="font-size: 38px;"></q-icon>
              Our Title
            </div>
          </q-card-section>
          <q-card-section class="text-left">
            Your full focus is on your App's content rather than all other boilerplating stuff around it (build system,
            layout, and much more). You'll be spending time only on what matters, which is your product. Quasar greatly
            increases your
            productivity.
          </q-card-section>
        </q-card>
      </div>
    </section>
    <section>
      <div class="row justify-center q-pa-lg">
        <q-card class="col-12 col-md-5 no-shadow">
          <q-card-section class="row">
            <div class="col-12 text-h6 text-center">
              Company info
            </div>
          </q-card-section>
          <q-card-section class="text-left">
            Your full focus is on your App's content rather than all other boilerplating stuff around it (build system,
            layout, and much more). You'll be spending time only on what matters, which is your product. Quasar greatly
            increases your
            productivity.
          </q-card-section>
        </q-card>
        <q-card class="col-12 col-md-5 no-shadow">

          <q-card-section class="row">
            <div class="col-12 text-h6 text-center">
              Contact us
            </div>
          </q-card-section>
          <q-card-section class="text-left">
            <q-list>
              <q-item>
                <q-item-section avatar>
                  <q-icon color="primary" name="phone"/>
                </q-item-section>
                <q-item-section>
                  <q--item-label>91289082616</q--item-label>
                </q-item-section>
              </q-item>

              <q-item>
                <q-item-section avatar>
                  <q-icon color="primary" name="place"/>
                </q-item-section>
                <q-item-section>
                  <q-item-label>Pune, India</q-item-label>
                </q-item-section>
              </q-item>

              <q-item>
                <q-item-section avatar>
                  <q-icon color="amber" name="mail"/>
                </q-item-section>
                <q-item-section>
                  <q-item-label>praitkpatel@gmail.com</q-item-label>
                </q-item-section>
              </q-item>
            </q-list>
          </q-card-section>
        </q-card>
      </div>
    </section>
    <section class="flex row flex-center q-py-sm layout_bg">
      <div class="flex col-12 q-pa-xs flex-center">
        <q-icon name="fab fa-github" color="white" size="md">
        </q-icon>
      </div>
      <div class="text-weight-bold text-white text-caption">
        Copyright © {{ year }} Pratik Patel
      </div>
    </section>
  </q-page>
</template>

<script>
    export default {
        name: 'PageIndex',
        data() {
            return {
                year: (new Date()).getFullYear(),
                expanded: false,
            }
        }
    }
</script>
<style>
  .layout_bg {
    background: linear-gradient(135deg, #699cc3 10%, #1a6bc3 100%)
  }
</style>
