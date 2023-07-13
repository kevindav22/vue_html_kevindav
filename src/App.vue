<template>
  <HeaderComponent></HeaderComponent>
  <section class="hero">
    <div class="container col-xxl-8 px-4 py-5">
      <div class="row flex-lg-row-reverse align-items-center">
        <div class="col-10 col-sm-8 col-lg-6">
          <lottie-player src="https://lottie.host/bdbf3c8f-5301-4c75-9a46-6a9fddd3f2e6/EseEMq4Ykr.json" background="transparent" speed="1" style="width: 100%; height: auto" loop autoplay></lottie-player>
        </div>
        <div class="col-lg-6">
          <h1 class="display-5 fw-bold lh-1 mb-3">Kevin David Richard</h1>
          <p class="lead">Ini adalah Project Vue.js pertama saya dengan mengikuti tutorial yang diberikan pak dosen kepada saya dalam pembuatanya saya mengalami banyak kesulitan</p>
          <div class="d-grid gap-2 d-md-flex justify-content-md-start">
            <button type="button" class="btn btn-primary btn-lg px-4 me-md-2" fdprocessedid="7sokev">hubungi</button>
            <button type="button" class="btn btn-outline-primary btn-lg px-4" fdprocessedid="1vr6yo">Github</button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
export default {
  name: 'App',
  components: {
    HeaderComponent,
  },
};
</script>

<style></style>
