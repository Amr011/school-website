<script>
export default {
  name: 'faq',
  data() {
    return {
      counters: 4,
      open: false,
    }
  },
}
</script>
<template>
  <!-- faq-section -->
  <div class="mx-auto my-4 max-w-[1100px] px-4">
    <div
      class="grid grid-cols-1 grid-rows-2 items-center gap-16 lg:grid-cols-2 lg:grid-rows-1 xl:grid-cols-2 xl:grid-rows-1"
    >
      <!-- faq-content -->
      <div class="">
        <div class="flex items-center text-yellow-400">
          <h3 class="mb-0">لديك سؤال</h3>
          <div class="mr-2 mt-[34px] h-0.5 w-4 bg-yellow-400"></div>
        </div>
        <h1 class="mt-0 text-[42px] font-extrabold">اكثر الأسئلة الشائعة تداولاً حول المدرسة!</h1>
        <p class="max-w-[450px] text-gray-500">
          نحن مدرسة افتراضية نقوم بتدريس المنهاج السوري وفقاً لوزارة التربية والتعليم في سوريا
        </p>
      </div>
      <!-- faq-list -->
      <div class=" ">
        <div class="flex justify-start">
          <div class="w-full space-y-4">
            <div
              @click="open = !open"
              v-for="counter in counters"
              :key="counter"
              class="w-full cursor-pointer rounded-2xl outline outline-blue-500"
            >
              <div class="flex w-full items-center justify-between">
                <p class="my-2 py-0 px-4 text-gray-500">هل انتم مرخصين من قبل وزارة التربية؟</p>
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="16"
                  height="16"
                  fill="currentColor"
                  class="bi bi-chevron-down px-4"
                  viewBox="0 0 16 16"
                >
                  <path
                    fill-rule="evenodd"
                    d="M1.646 4.646a.5.5 0 0 1 .708 0L8 10.293l5.646-5.647a.5.5 0 0 1 .708.708l-6 6a.5.5 0 0 1-.708 0l-6-6a.5.5 0 0 1 0-.708z"
                  />
                </svg>
              </div>
              <div v-if="open == true" class="px-4 py-2">
                نحن مدرسة نقوم بتدريس المنهاج السوري بكفاءة
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style></style>
