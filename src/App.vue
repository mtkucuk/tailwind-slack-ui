<template>
  <div class="flex h-screen">
    <!-- Left Sidebar -->
    <div class="w-64 bg-gray-900">
      <div class="w-full h-screen overflow-hidden">
        <partials-sidebar></partials-sidebar>
      </div>
    </div>
    <!-- Main Content -->
    <div class="flex-1 overflow-y-auto">
      <!-- Main Content Header -->
      <header class="bg-white shadow-lg py-4 px-6">

      </header>
      <!-- Main Content Body -->
      <div class="p-6">
        <!-- Body Content -->
      </div>
    </div>
  </div>

</template>

<script>
import sidebar from "@/partials/sidebar";

export default {
  name: 'App',
  components: {
    'partials-sidebar':sidebar
  }
}
</script>
