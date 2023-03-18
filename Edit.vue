<script setup>
function handleUpdateStudentForm(){
  console.log("Updated");
}
</script>

<template>
  <div class="shadow-md pb-6">
    <div class="bg-indigo-600 p-4">
      <h1 class="text-3xl font-bold text-center text-white">
        Edit Student
      </h1>
    </div>
    <form @submit.prevent="handleUpdateStudentForm" class="w-full">
      <div class="flex-items-center m-6">
        <div class="w-1/5">
          <label for="stuid" class="font-medium"> ID : </label>
        </div>
      </div>
    </form>
  </div>
<h1 class="text-3xl font-bold underline">
    Edit
  </h1>
</template>

<style scoped>
</style>
