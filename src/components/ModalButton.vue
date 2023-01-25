<template>
  <button class="bg-green-400 text-white" type="button" @click="openModal()">Modal</button>
</template>


<script>
export default {
  setup() {
    return {
      openModal() {
        let modal = document.getElementById('tw-modal')
        modal.classList.remove('hidden')
        modal.classList.add('block')
      }
    }
  }
}
</script>


<style lang="scss" scoped>

</style>