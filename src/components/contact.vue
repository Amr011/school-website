<script>
import emailjs from 'emailjs-com'

export default {
  name: 'contact',
  data() {
    return {
      name: '',
      email: '',
      message: '',
    }
  },
  methods: {
    sendEmail(e) {
      try {
        emailjs.sendForm(
          'service_ushygk9',
          'template_4nu663b',
          e.target,
          'amraboras109@gmail.com',
          {
            name: this.name,
            email: this.email,
            message: this.message,
          }
        )
      } catch (error) {
        console.log({ error })
      }
      // Reset form field
      this.name = ''
      this.email = ''
      this.message = ''
    },
  },
}
</script>
<template>
  <!-- contact-section -->
  <div class="mx-auto my-20 max-w-[1100px] px-4">
    <div
      class="grid grid-cols-1 grid-rows-2 items-center gap-16 lg:grid-cols-2 lg:grid-rows-1 xl:grid-cols-2 xl:grid-rows-1"
    >
      <!-- contact-content -->
      <div class="row-start-1 lg:row-start-1 xl:col-start-2 xl:row-start-1">
        <div class="flex items-center text-yellow-400">
          <h3 class="mb-0">التواصل</h3>
          <div class="mr-2 mt-[34px] h-0.5 w-4 bg-yellow-400"></div>
        </div>
        <h1 class="mt-0 text-[42px]">لديك استفسار؟ تواصل معنا حالاً!</h1>

        <div class="grid gap-1 text-xl">
          <a
            href="tel:+9639322338018"
            class="mr-2 flex items-start rounded-md py-1 font-medium text-gray-400 no-underline"
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              fill="currentColor"
              class="bi bi-telephone-fill text-blue-500"
              viewBox="0 0 16 16"
            >
              <path
                fill-rule="evenodd"
                d="M1.885.511a1.745 1.745 0 0 1 2.61.163L6.29 2.98c.329.423.445.974.315 1.494l-.547 2.19a.678.678 0 0 0 .178.643l2.457 2.457a.678.678 0 0 0 .644.178l2.189-.547a1.745 1.745 0 0 1 1.494.315l2.306 1.794c.829.645.905 1.87.163 2.611l-1.034 1.034c-.74.74-1.846 1.065-2.877.702a18.634 18.634 0 0 1-7.01-4.42 18.634 18.634 0 0 1-4.42-7.009c-.362-1.03-.037-2.137.703-2.877L1.885.511z"
              />
            </svg>

            <p class="my-0 mr-4">018 338 932 963 +</p>
          </a>
          <a
            href="mailto:amraboras109@gmail.com"
            class="mr-2 flex items-start rounded-md py-1 font-medium text-gray-400 no-underline"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              fill="currentColor"
              class="bi bi-envelope-fill text-blue-500"
              viewBox="0 0 16 16"
            >
              <path
                d="M.05 3.555A2 2 0 0 1 2 2h12a2 2 0 0 1 1.95 1.555L8 8.414.05 3.555ZM0 4.697v7.104l5.803-3.558L0 4.697ZM6.761 8.83l-6.57 4.027A2 2 0 0 0 2 14h12a2 2 0 0 0 1.808-1.144l-6.57-4.027L8 9.586l-1.239-.757Zm3.436-.586L16 11.801V4.697l-5.803 3.546Z"
              />
            </svg>

            <p class="my-0 mr-4">amraboras109@gmail.com</p>
          </a>

          <a
            href="https://www.google.com/maps/@24.1933625,56.0270695,10z"
            target="_blank"
            class="mr-2 flex items-start rounded-md py-1 font-medium text-gray-400 no-underline"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              fill="currentColor"
              class="bi bi-geo-alt-fill text-blue-500"
              viewBox="0 0 16 16"
            >
              <path
                d="M8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10zm0-7a3 3 0 1 1 0-6 3 3 0 0 1 0 6z"
              />
            </svg>
            <p class="my-0 mr-4">سوريا , السويداء , طريق قنوات , برج العميد طـ 6</p>
          </a>
          <a
            href="https://calendar.google.com/calendar/u/0/r"
            target="_blank"
            class="mr-2 flex items-start rounded-md py-1 font-medium text-gray-400 no-underline"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="32"
              height="32"
              fill="currentColor"
              class="bi bi-calendar-check-fill text-blue-500"
              viewBox="0 0 16 16"
            >
              <path
                d="M4 .5a.5.5 0 0 0-1 0V1H2a2 2 0 0 0-2 2v1h16V3a2 2 0 0 0-2-2h-1V.5a.5.5 0 0 0-1 0V1H4V.5zM16 14V5H0v9a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2zm-5.146-5.146-3 3a.5.5 0 0 1-.708 0l-1.5-1.5a.5.5 0 0 1 .708-.708L7.5 10.793l2.646-2.647a.5.5 0 0 1 .708.708z"
              />
            </svg>
            <p class="my-0 mr-4">
              جميع ايام الأسبوع ما عدا الجمعة والسبت من الساعة 08:00 صباحاً حتى الساعة 05:00 مساءً
            </p>
          </a>
        </div>
      </div>

      <!-- contact-form -->
      <div class="w-full">
        <div class="flex w-full justify-start">
          <form class="w-full" method="post">
            <div class="w-full">
              <p class="m-0 p-0">الاسم الكامل</p>
              <input
                class="m-0 w-full rounded-lg border border-solid border-blue-500 py-3 outline-1 outline-blue-500"
                type="text"
                v-model="name"
                name="name"
                placeholder="ادخل اسمك الكامل هنا"
              />
            </div>
            <div class="">
              <p class="m-0 p-0">البريد الإلكتروني</p>
              <input
                class="m-0 w-full rounded-lg border border-solid border-blue-500 py-3 outline-1 outline-blue-500"
                type="text"
                v-model="email"
                name="email"
                placeholder="ادخل بريدك الإلكتروني هنا"
              />
            </div>
            <div class="">
              <p class="m-0 p-0">الرسالة</p>
              <textarea
                rows="5"
                class="m-0 w-full rounded-lg border border-solid border-blue-500 py-3 outline-1 outline-blue-500"
                type="text"
                v-model="message"
                name="message"
                placeholder="ادخل رسالتك هنا"
              />
            </div>
            <div class="w-full">
              <input
                type="submit"
                class="my-8 mx-auto w-full cursor-pointer rounded-md border-solid border-blue-500 bg-blue-500 py-2 text-lg font-medium text-white"
                value="إرسال"
              />
            </div>
          </form>
        </div>
      </div>
    </div>
  </div>
</template>

<style></style>
