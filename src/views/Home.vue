<script setup>
import Hero from "../components/Hero.vue";
import About from "../components/About.vue";

const name = "Sy. Zevani Ananda Zellery";
const job = "Mahasiswi";
const image = "https://blue.kumparan.com/image/upload/fl_progressive,fl_lossy,c_fill,q_auto:best,w_640/v1634025439/01ha9vjw0a1ffcwnq1phnvn2vf.jpg"; // Resolve conflict in image URL

</script>
<template>
  <Hero :name="name" :job="job" :description="description" :image="image" />
  <About
    description="Perkenalkan nama saya Sy. Zevani Ananda Zellery , saya lahir 26 Oktober 2005 , saya berasal dari kota Pekanbaru. Saya melanjutkan studi S1 (strata satu) di Universitas Islam Riau dan mengambil jurusan Teknik Informatika, kini telah memasuki semester 4."
    whatsApp="https://wa.me/85264200657"
    github="https://github.com/zevani"
    instagram="https://www.instagram.com/anandaazvn/#"
  />
</template>
