<template>
  <div>
    Aniket
    <v-page
      ref="page"
      :language="'en'"
      :page-size-menu="false"
      :info="false"
      :total-row="100"
      :first="false"
      :last="false"
      :border="false"
      align="center"
    />
  </div>
</template>

<script>
export default {
  mounted() {
    this.$refs.page.pageNumberSize = 6;
  },
};
</script>
