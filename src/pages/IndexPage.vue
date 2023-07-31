<template>
  <div class="main-container">
    <div class="flex home-container row full-width q-pb-xl">
      <div class="col-6 text-center self-center">
        <h4 class="q-pa-none q-ma-none text-white">Hello,</h4>
        <h4 class="q-pa-none q-ma-none text-weight-bold text-white">
          I'M Jhousua Jumalon
        </h4>
        <div class="text-subtitle1 text-weight-bold text-grey">
          Web Designer | Web Developer
        </div>
        <q-btn class="q-ma-lg" outline style="color: #daa520" label="Contact" />
      </div>
      <div class="col-6 self-center flex justify-center">
        <q-avatar class="" size="200px">
          <img src="https://cdn.quasar.dev/img/avatar.png" />
        </q-avatar>
      </div>
    </div>

    <div class="about-container q-pa-none q-ma-none">
      <div>
        <h4 class="text-center q-mt-none q-mb-none q-pt-xl text-weight-bold">
          About me
        </h4>
        <q-separator class="q-mb-xl" inset />
      </div>
      <div class="flex justify-evenly row">
        <div class="text-center self-center col-6">
          <q-card class="my-card">
            <img src="https://cdn.quasar.dev/img/mountains.jpg" />
          </q-card>
        </div>
        <div class="self-center col-6 text-left">
          <h6 class="q-ma-none q-px-xl text-weight-bold text-warning">
            I Am a Web Designer and Developer
          </h6>

          <div class="q-px-xl text-subtitle1 q-mt-md">
            orem ipsum dolor sit amet, consectetur adipiscing elit. Praesent
            massa sem, luctus vitae pellentesque ut, gravida in odio. Morbi
            vehicula ex diam, eget placerat augue scelerisque vel. Vestibulum at
            sodales neque, sit amet rhoncus nibh. Nunc et porta mi. Sed varius,
            turpis quis malesuada ullamcorper, orci ex hendrerit purus, ac
            laoreet dui dui eget elit.
          </div>
          <div class="q-px-xl text-subtitle1 q-mt-md">
            orem ipsum dolor sit amet, consectetur adipiscing elit. Praesent
            massa sem, luctus vitae pellentesque ut, gravida in odio. Morbi
            vehicula ex diam, eget placerat augue scelerisque vel. Vestibulum at
            sodales neque, sit amet rhoncus nibh. Nunc et porta mi. Sed varius,
            turpis quis malesuada ullamcorper, orci ex hendrerit purus, ac
            laoreet dui dui eget elit.
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.home-container {
  height: 700px;
  background-image: url(https://images.pexels.com/photos/3308588/pexels-photo-3308588.jpeg?auto=compress&cs=tinysrgb&w=1600);
  background-size: cover;
  background-position: center;
}
.about-container {
  height: 700px;
}
</style>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "IndexPage",
});
</script>
