<script setup>
</script>

<template>
  <div class="shadow-md pb-6">
    <table class="table-auto w-full">
      <thead class="bg-slate-600 text-white">
        <tr>
          <th class="py-1">ID</th>
          <th class="py-1">Name</th>
          <th class="py-1">Email</th>
        </tr>
      </thead>
      <tbody class="text-center">
        <tr>
          <td class="py-2">1</td>
          <td class="py-2">Rijwan</td>
          <td class="py-2">rijwan@gmail.com</td>
        </tr>
      </tbody>
    </table>
    <div class="m-8 flex justify-center">
      <RouterLink :to="{name : 'list'}">
        <button type="button" class="bg-emerald-700 text-white font-medium py-2 rounded-md px-6 hover:bg-emerald-800 mr-6">
          Back to Home
        </button>
      </RouterLink>
    </div>
  </div>
</template>

<style scoped>
</style>
