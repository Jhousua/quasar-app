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
        <q-btn
          class="q-ma-lg"
          outline
          style="color: goldenrod"
          label="Contact"
        />
      </div>
      <div class="col-6 self-center flex justify-center">
        <q-avatar class="" size="200px">
          <img src="https://cdn.quasar.dev/img/avatar.png" />
        </q-avatar>
      </div>
    </div>

    <div class="about-container bg-grey q-pa-none q-ma-none">
      <div>
        <h4 class="text-center q-mt-none q-pt-xl">About me</h4>
      </div>
      <div class="flex row">
        <div class="col-6 text-center self-center">
          <q-img size="20px" src="/heroimg.png" :ratio="1" />
        </div>
        <div class="col-6 self-center flex justify-center">text</div>
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
