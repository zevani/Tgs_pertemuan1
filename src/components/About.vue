<!-- src/components/About.vue -->
<script setup>
import whatsAppIcon from '../assets/whatsApp.svg';
import InstagramIcon from '../assets/instagram.svg';
import GitHubIcon from '../assets/github-mark.png'; // Adjusted import path

const props = defineProps({
  smallDescription: String,
  description: String,
  github: String,
  whatsApp: String,
  instagram: String,
});
</script>

<template>
  <div class="bg-light p-5">
    <div class="container text-center">
      <div class="row">
        <div class="col-md-12">
          <h1 class="fw-bold">About Me</h1>
          <div class="d-flex justify-content-center" style="width: 100%">
            <p style="max-width: 30rem; font-size: 20px">
              {{ smallDescription }}
            </p>
          </div>
          <p style="max-width: 40rem" class="mx-auto">
            {{ description }}
          </p>
          <div class="d-flex align-items-center justify-content-center gap-2">
            <a :href="'https://web.whatsapp.com/' + whatsApp" target="_blank">
              <img
                style="width: 30px; height: 30px"
                :src="whatsAppIcon"
                alt="WhatsApp Icon"
              />
            </a>
            <a :href="'https://github.com/' + github" target="_blank">
              <img
                style="width: 30px; height: 30px"
                :src="GitHubIcon"
                alt="GitHub Icon"
              />
            </a>
            <a :href="'https://instagram.com/' + instagram" target="_blank">
              <img
                style="width: 30px; height: 30px"
                :src="InstagramIcon"
                alt="Instagram Icon"
              />
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
/* Add any additional styles here */
</style>
