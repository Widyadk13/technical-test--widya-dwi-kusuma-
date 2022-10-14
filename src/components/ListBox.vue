<script setup>

</script>
<template>
<div class="container mx-auto">
  <!-- radio -->
  <div class="mb-3">Jenjang Pendidikan: {{ Pendidikan }}</div>

    <input type="radio" id="one" value="One" v-model="picked" />
      <label for="one"> Diploma dan Sarjana </label>
    <input type="radio" id="two" value="Two" v-model="picked" />
      <label for="two"> Magister </label>
    <input type="radio" id="two" value="Two" v-model="picked" />
      <label for="two"> Doktoral </label>

  <!-- form -->
  <div class="flex items-center mt-8 w-screen">
    <div class="border border-gray-200 rounded p-10">
    <div class="mb-4">
      <label class="block" mb-1></label>
      <input type="text" class="border" border-gray-400 py-2 px-4 w-full placeholder="Nama Lengkap"/>
    </div>
    <div class="flex mb-4 mr-2">
      <label class="block" mb-1></label>
      <input type="text" class="border mr-3" border-gray-400 py-2 px-4 w-full placeholder="Tempat Lahir"/>
    
      <label class="block" mb-1></label>
      <input type="date" class="border" border-gray-400 py-2 px-4 w-full placeholder="Tanggal Lahir"/>
    </div>
    </div>
    </div>
</div>
</template>