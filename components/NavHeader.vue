<template>
  <div class="border-b-2 border-gray-200">
    <div class="container mx-auto px-6">
      <nav class="py-3 w-full flex items-center justify-between">
        <n-link class="flex items-center flex-shrink" to="/">
          <div class="flex-shrink-0">
            <favicon class="w-8 h-8"/>
          </div>
          <div class="text-lg font-bold ml-4 text-gray-800 hover:text-red-600">
            <div class="truncate">
              Project HeartCode 2020
            </div>
          </div>
        </n-link>
      </nav>
    </div>
  </div>
</template>

<script>
import Favicon from "@/components/Favicon";

export default {
  name: "NavHeader",
  components: {Favicon},
  computed: {
    currentPath() {
      return this.$route.path
    }
  }
}
</script>

<style scoped>

</style>
