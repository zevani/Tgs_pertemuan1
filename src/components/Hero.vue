<script setup>
const props = defineProps({
  name: String,
  job: String,
  description: String,
  image: String,
});
</script>

<template>
  <div class="container d-flex align-items-center justify-content-center" style="height: 100vh; width: 100vh">
    <div class="row d-flex align-items-center items-centers">
      <div class="col-md-6 d-grid gap-3" style="max-width: 50rem">
        <h1 class="fw-bold" style="font-size: 3rem">{{ props.name }}</h1>
        <h4>{{ props.job }}</h4>
      </div>
      <div class="col-md-6">
        <!-- Resolved conflict in the img src attribute -->
        <img
          src="https://blue.kumparan.com/image/upload/fl_progressive,fl_lossy,c_fill,q_auto:best,w_640/v1634025439/01ha9vjw0a1ffcwnq1phnvn2vf.jpg" 
          alt=""
          class="img-fluid rounded-5"
        />
      </div>
    </div>
  </div>
</template>
