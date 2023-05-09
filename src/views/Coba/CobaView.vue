<script setup>
import NavbarDarkCustom from "../../layouts/sections/navigation/navbars/components/NavbarDarkCustom.vue";
import HeaderOneCustom from "../../layouts/sections/page-sections/page-headers/components/HeaderOneCustom.vue";
import PresentationExampleCustomVue from "../Presentation/Sections/PresentationExampleCustom.vue";
import FooterDefaultCustom from "../../examples/footers/FooterDefaultCustom.vue";
import data from "../Presentation/Sections/Data/designBlocksData.js";
</script>
<template>
  <div class="navbar-fixed-top">
    <NavbarDarkCustom />
  </div>
  <HeaderOneCustom />
  <div class="container mb-5" id="startdong">
    <div class="row">
      <div class="col-lg-12 mx-auto">
        <PresentationExampleCustomVue :data="data" />
      </div>
    </div>
  </div>
  <FooterDefaultCustom />
</template>
<style>
.navbar-fixed-top {
  position: fixed;
  top: 0;
  width: 100%;
  z-index: 999;
}
</style>
