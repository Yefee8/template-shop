<template>
  <div class="card bg-primary flex flex-col text-white rounded-lg pb-4 w-cardmobile md:w-card">
    <div
      class="mainphoto flex justify-center rounded-t-lg py-8 md:py-16 items-center text-sprimary text-lg md:text-2xl bg-black"
    >
      <span class="text-center">template <br> photo</span>
    </div>

    <div class="flex mt-4 md:mt-8 text-lg md:text-2xl font-medium justify-evenly">
      <span>
        {{title}}
      </span>
      <span>
        $75
      </span>
    </div>

    <p class="text-xs mt-4 md:mt-8 text-center mx-6 md:text-md">
      Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's
      standard dummy text ever since the 1500s!
    </p>

    <div class="flex justify-center">
      <button
        class="mt-4 md:mt-8 w-24 py-2 text-sprimary text-md md:text-2xl border-2 border-sprimary hover:bg-sprimary hover:text-white transition duration-300"
        style="border-radius: 50px;"
      >
        buy
      </button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'CardComponent',
  props: ['title']
}
</script>

<style scoped>

</style>
