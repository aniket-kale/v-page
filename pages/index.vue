<template>
  <div class="m-10">
    <div>
      <h3>Pagination</h3>
    </div>
    <v-page
      ref="page"
      :language="'en'"
      :page-size-menu="false"
      :info="false"
      :total-row="100"
      :first="false"
      :last="false"
      :border="true"
      align="left"
    />
  </div>
</template>

<script>
export default {
  mounted() {
    this.$refs.page.pageNumberSize = 5;
  },
};
</script>
