<template>
  <div
    class="
      absolute
      -bottom-28
      left-0
      w-2/3
      h-1/3
      px-10
      flex flex-col
      max-w-full max-h-full
    "
  >
    <h2 class="text-xl text-gray-600 font-medium pb-5">Choose Your Courier</h2>
    <div
      class="
        bg-green-100
        border-2 border-green-400
        w-3/4
        h-24
        flex
        justify-between
        px-4
      "
    >
      <div class="flex justify-center space-x-4 pb-5">
        <div class="text-green-500 pt-4">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-5 w-5"
            viewBox="0 0 20 20"
            fill="currentColor"
          >
            <path
              fill-rule="evenodd"
              d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-11a1 1 0 10-2 0v2H7a1 1 0 100 2h2v2a1 1 0 102 0v-2h2a1 1 0 100-2h-2V7z"
              clip-rule="evenodd"
            />
          </svg>
        </div>
        <div class="flex flex-col">
          <h1 class="text-xl text-gray-900 font-medium">FedEx Int</h1>
          <p class="text-xl text-gray-500 h-10 w-2/3">
            You can still count on the day and time shipment arrives in 2-3 Days
            shipping
          </p>
        </div>
      </div>
      <div class="flex space-x-0">
        <span class="block text-3xl font-bold text-blue-900">Fed</span>
        <span class="block text-3xl font-bold text-yellow-600">Ex.</span>
      </div>
    </div>
    <div
      class="
        bg-gray-100
        border-2 border-gray-400
        w-3/4
        h-18
        mt-4
        px-6
        bottom-0
        left-0
        mx-w-full
        max-h-full
      "
    >
      <div class="flex justify-between">
        <div class="flex space-x-4">
          <div class="text-gray-300 pt-2">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-5 w-5"
              viewBox="0 0 20 20"
              fill="currentColor"
            >
              <path
                fill-rule="evenodd"
                d="M6.267 3.455a3.066 3.066 0 001.745-.723 3.066 3.066 0 013.976 0 3.066 3.066 0 001.745.723 3.066 3.066 0 012.812 2.812c.051.643.304 1.254.723 1.745a3.066 3.066 0 010 3.976 3.066 3.066 0 00-.723 1.745 3.066 3.066 0 01-2.812 2.812 3.066 3.066 0 00-1.745.723 3.066 3.066 0 01-3.976 0 3.066 3.066 0 00-1.745-.723 3.066 3.066 0 01-2.812-2.812 3.066 3.066 0 00-.723-1.745 3.066 3.066 0 010-3.976 3.066 3.066 0 00.723-1.745 3.066 3.066 0 012.812-2.812zm7.44 5.252a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                clip-rule="evenodd"
              />
            </svg>
          </div>
          <div class="text-xl text-gray-900 font-medium">DHL Express</div>
        </div>

        <div class="text-3xl font-bold text-red-600">DNL</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ContentFooter",
};
</script>

