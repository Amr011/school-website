<script>
export default {
  name: 'mainNavbar',
}
</script>
<template>
  <!-- navbar-main -->
  <div class="fixed left-0 right-0 top-0 z-50">
    <!-- navbar-small -->
    <div class="bg-blue-500 px-4">
      <div class="mx-auto flex max-w-[1100px] justify-end">
        <!-- contact-info -->
        <ul class="my-1 flex-1 list-none justify-end text-left text-white sm:flex md:flex">
          <li class="ml-0 md:ml-2 lg:ml-2 xl:ml-2">
            <a
              href="mailto:amraboras109@gmail.com"
              class="flex items-center justify-end text-white no-underline duration-100 hover:text-blue-100"
            >
              <p class="m-0 ml-2">amraboras109@gmail.com</p>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="20"
                height="20"
                fill="currentColor"
                class="bi bi-envelope-fill"
                viewBox="0 0 16 16"
              >
                <path
                  d="M.05 3.555A2 2 0 0 1 2 2h12a2 2 0 0 1 1.95 1.555L8 8.414.05 3.555ZM0 4.697v7.104l5.803-3.558L0 4.697ZM6.761 8.83l-6.57 4.027A2 2 0 0 0 2 14h12a2 2 0 0 0 1.808-1.144l-6.57-4.027L8 9.586l-1.239-.757Zm3.436-.586L16 11.801V4.697l-5.803 3.546Z"
                />
              </svg>
            </a>
          </li>
          <li class="mr-0 md:mr-2 lg:mr-2 xl:mr-2">
            <a
              href="tel:+963932338018"
              class="flex items-center justify-end text-white no-underline duration-100 hover:text-blue-100"
            >
              <p class="m-0 ml-1">963932338018+</p>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="20"
                height="20"
                fill="currentColor"
                class="bi bi-telephone-fill"
                viewBox="0 0 16 16"
              >
                <path
                  fill-rule="evenodd"
                  d="M1.885.511a1.745 1.745 0 0 1 2.61.163L6.29 2.98c.329.423.445.974.315 1.494l-.547 2.19a.678.678 0 0 0 .178.643l2.457 2.457a.678.678 0 0 0 .644.178l2.189-.547a1.745 1.745 0 0 1 1.494.315l2.306 1.794c.829.645.905 1.87.163 2.611l-1.034 1.034c-.74.74-1.846 1.065-2.877.702a18.634 18.634 0 0 1-7.01-4.42 18.634 18.634 0 0 1-4.42-7.009c-.362-1.03-.037-2.137.703-2.877L1.885.511z"
                />
              </svg>
            </a>
          </li>
        </ul>
      </div>
    </div>

    <!-- navbar-big -->
    <div class="bg-white px-4 shadow-md">
      <div
        class="container mx-auto grid max-w-[1100px] grid-cols-3 items-center justify-center py-3 lg:grid-cols-2 lg:py-0 xl:grid-cols-2 xl:py-0"
      >
        <!-- logo -->
        <div class="flex justify-start">
          <img src="../../public/images/logo2.png" alt="LOGO" />
        </div>
        <!-- navigation-bar -->
        <div class="flex justify-end">
          <ul class="hidden list-none text-gray-500 lg:inline-flex xl:inline-flex">
            <li class="mx-2">
              <a href="#" class="text-gray-500 no-underline duration-500 hover:text-black"
                >الرئيسية</a
              >
            </li>
            <li class="mx-2">
              <a href="#" class="text-gray-500 no-underline duration-500 hover:text-black"
                >من نحن</a
              >
            </li>
            <li class="mx-2">
              <a href="#" class="text-gray-500 no-underline duration-500 hover:text-black"
                >التواصل</a
              >
            </li>
            <li class="group mx-2">
              <a href="#" class="text-gray-500 no-underline duration-500 hover:text-black"
                >التعليم
                <!-- List -->
                <div
                  class="absolute left-0 rounded-[10px] bg-white opacity-0 shadow-md outline outline-[0.5px] outline-blue-500 group-hover:opacity-100 lg:left-0 xl:left-auto"
                >
                  <div class="px-4 py-2">
                    <a href="#" class="m- text-gray-600 no-underline duration-500 hover:text-black">
                      التواصل معنل</a
                    >
                  </div>
                  <div class="px-4 py-2">
                    <a href="#" class="m- text-gray-600 no-underline duration-500 hover:text-black">
                      التواصل معنل</a
                    >
                  </div>
                </div>
              </a>
            </li>
          </ul>
        </div>

        <!-- call-to-action -->
        <!-- 
      <div class="my-4 hidden justify-end lg:flex xl:flex">
        <a href="#" class="rounded-md px-10 py-1 text-lg font-bold text-blue-500 no-underline outline transition-all duration-500 hover:bg-blue-500 hover:text-white">سجل الآن</a>
      </div>  -->

        <!-- nav-menu -->
        <div class="flex justify-end lg:hidden xl:hidden">
          <a href="#" class="font-bold text-blue-400 no-underline">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="48"
              height="48"
              fill="currentColor"
              class="bi bi-list"
              viewBox="0 0 16 16"
            >
              <path
                fill-rule="evenodd"
                d="M2.5 12a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5z"
              />
            </svg>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<style></style>
