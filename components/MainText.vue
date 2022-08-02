<template>
  <div class="flex mt-20 md:mt-40 flex-col font-medium text-white">
    <div class="main text-md md:text-3xl w-full">
      <span>Let's buy some <span class="text-primary border-b-2 border-primary">templates</span>!</span>
    </div>
    <div class="mt-20 md:mt-40 w-48 md:w-96 text-xs text-lg font-normal">
      <p>
        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the
        industry's standard dummy text ever since the 1500s!
      </p>
    </div>

    <button
      class="mt-20 md:mt-40 w-24 py-2 text-primary text-md md:text-2xl border-2 border-primary hover:bg-primary font-semibold hover:text-white transition duration-300"
      style="border-radius: 50px;"
    >
      buy
    </button>
  </div>
</template>

<script>
export default {
  name: 'MainTextComponent'
}
</script>

<style scoped>

</style>
