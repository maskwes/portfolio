<template>
  <c-header></c-header>
  <c-main>
    <slot></slot>
  </c-main>
  <c-footer></c-footer>
</template>

<script lang="ts" setup>

import CHeader from "../components/ui/navigation/CHeader.vue";
import CFooter from "../components/ui/navigation/CFooter.vue";
import CMain from "../components/ui/wrappers/CMain.vue";</script>

