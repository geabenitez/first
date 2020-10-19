<template>
  <div class="flex flex-row border-b justify-between py-4">
    <span>VUEJS</span>
    <ul class="flex flex-row space-x-6">
      <li v-for="(m, k) of menu" :key="k" class="cursor-pointer hover:font-black">{{ m }}</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Header',
  data(){
    return {
      menu: [
        'Inicio',
        'Productos',
        'Sobre nosotros',
        'Contacto',
        'Otro',
      ]
    }
  }
}
</script>