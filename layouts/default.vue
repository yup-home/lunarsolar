<template>
  <main>
    <a-layout>
      <a-layout>
        <a-layout-content style="padding: 5%; height: 1000px;">
          <slot/>
        </a-layout-content>
      </a-layout>
      <a-layout>
        <a-layout-footer></a-layout-footer>
      </a-layout>
    </a-layout>
  </main>
</template>

<script>
export default {
  name: "default"
}
</script>

<style scoped>

</style>