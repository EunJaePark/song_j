<template>
  <div class="main_component">
    <router-link to="/detail" class="goBtn">치료사 소개</router-link>
  </div>
</template>

<script>
export default {
  methods: {
    goDetail() {
      this.$router.push("detail");
    }
  }
};
</script>

<style></style>
