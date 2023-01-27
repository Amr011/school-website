<script>
export default {
  name: 'hero',
}
</script>
<template>
  <!-- hero-section -->
  <div class="mx-auto my-40 max-w-[1100px] px-4">
    <div class="flex justify-center">
      <div class="text-center">
        <!-- logo-img -->
        <img
          src="../../public/images/logo.png"
          class="max-h-[500px] max-w-[500px]"
          alt="Hello World"
        />
        <!-- heading-title -->
        <h1>مدرسة الشام الدولية الافتراضية</h1>
        <!-- sub-title -->
        <p class="mx-auto mb-14 max-w-[450px] text-gray-500">
          نحن مدرسة افتراضية نقوم بتدريس المنهاج السوري وفقاً لوزارة التربية والتعليم في سوريا
          لوزارة التربية والتعليم في سوريا
        </p>
        <!-- call-to-action -->
        <div
          class="m-auto grid max-w-[400px] grid-cols-1 justify-center md:grid-cols-2 lg:grid-cols-2 xl:grid-cols-2"
        >
          <a
            href="#"
            class="my-2 ml-0 rounded-md bg-blue-500 px-10 py-1 text-lg font-bold text-white no-underline outline outline-blue-500 hover:bg-blue-500 hover:text-white md:ml-2 lg:ml-2 xl:ml-2"
            >سجل الآن</a
          >
          <a
            href="#"
            class="my-2 mr-0 rounded-md px-10 py-1 text-lg font-bold text-blue-500 no-underline outline transition-all duration-500 hover:bg-blue-500 hover:text-white hover:outline-blue-500 md:mr-2 lg:mr-2 xl:mr-2"
            >تواصل معنا</a
          >
        </div>
      </div>
    </div>
  </div>
</template>

<style></style>
