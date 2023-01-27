<script>
export default {
  name: 'about-top',
}
</script>

<template>
  <!-- about section -->
  <div class="mx-auto my-4 max-w-[1100px] px-4">
    <div
      class="lg:item-center grid grid-cols-1 grid-rows-2 items-start gap-16 md:items-center lg:grid-cols-2 lg:grid-rows-1 xl:grid-cols-2 xl:grid-rows-1 xl:items-center"
    >
      <!-- about-content -->
      <div class="row-start-2 lg:row-start-1 xl:row-start-1">
        <div class="flex items-center text-yellow-400">
          <h3 class="mb-0">من نحن</h3>
          <div class="mr-2 mt-[34px] h-0.5 w-4 bg-yellow-400"></div>
        </div>
        <h1 class="mt-0 text-[42px]">استمتع بافضل تجربة تعليمية عن بعد</h1>
        <p class="max-w-[450px] text-gray-500">
          نحن مدرسة افتراضية نقوم بتدريس المنهاج السوري وفقاً لوزارة التربية والتعليم في سوريا
        </p>
        <div class="flex">
          <a
            href="#"
            class="my-10 rounded-md px-10 py-1 text-lg font-bold text-blue-500 no-underline outline transition-all duration-500 hover:bg-blue-500 hover:text-white hover:outline-blue-500"
            >اكتشف المزيد</a
          >
        </div>
      </div>
      <!-- about-img -->
      <div class=" ">
        <div class="flex justify-start">
          <img
            src="../../public/images/1.png"
            class="h-auto w-full rounded-[40px] outline outline-blue-500 md:h-auto md:w-full lg:h-auto lg:w-full xl:h-auto xl:w-full"
            alt="Hello World"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<style></style>
