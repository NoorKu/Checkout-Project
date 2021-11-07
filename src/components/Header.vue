<template>
  <div>
    <header
      class="bg-green-400 w-full h-14 flex justify-between items-center pr-16"
    >
      <div class="flex justify-center items-center space-x-10 pl-16 text-white">
        <div class="flex justify-center items-center space-x-0 relative">
          <div class="text-white absolute -left-4">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-5 w-5"
              viewBox="0 0 20 20"
              fill="currentColor"
            >
              <path
                fill-rule="evenodd"
                d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM9 15a1 1 0 011-1h6a1 1 0 110 2h-6a1 1 0 01-1-1z"
                clip-rule="evenodd"
              />
            </svg>
          </div>
          <h3 class="font-semibold text-xl">DealShip</h3>
        </div>

        <a href="#" class="hover:text-gray-200">Home</a>
        <a href="#" class="hover:text-gray-200">Orders</a>
        <a href="#" class="hover:text-gray-200">Tracking</a>
      </div>
      <div class="flex justify-center items-center space-x-6">
        <div class="relative text-white font-semibold text-xl">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-5 w-5"
            viewBox="0 0 20 20"
            fill="currentColor"
          >
            <path
              d="M10 2a6 6 0 00-6 6v3.586l-.707.707A1 1 0 004 14h12a1 1 0 00.707-1.707L16 11.586V8a6 6 0 00-6-6zM10 18a3 3 0 01-3-3h6a3 3 0 01-3 3z"
            />
          </svg>
          <span
            class="
              absolute
              -right-0.5
              -top-1
              block
              w-2
              h-2
              bg-red-600
              text-red-500
              rounded-full
            "
          ></span>
        </div>
        <span class="block h-6 border-2 border-r-0 border-gray-300"></span>
        <div>
          <button class="w-10 h-10 bg-white rounded-full">
            <img
              src="../images/tes7.jpg"
              alt=""
              class="w-10 h-10 rounded-full"
            />
          </button>
        </div>
        <div class="text-white flex justify-center items-center space-x-2">
          <div class="flex justify-center items-center">
            <span class="block font-semibold text-xl">Hi,</span>
            <span>Melisa</span>
          </div>
          <div class="text-white font-semibold">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 20 20"
              fill="currentColor"
              class="w-8 h-8"
            >
              <path
                fill-rule="evenodd"
                d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                clip-rule="evenodd"
              />
            </svg>
          </div>
        </div>
      </div>
    </header>
    <div
      class="
        w-screen
        h-14
        flex
        justify-center
        items-center
        space-x-12
        bg-white
        shadow-xl
      "
    >
      <div class="flex justify-center items-center space-x-2 text-green-400">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-6 w-6"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"
          />
        </svg>
        <h2 class="text-gray-300 text-2xs">Shopping</h2>
      </div>
      <div class="flex justify-center items-center space-x-2 text-green-400">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-5 w-5"
          viewBox="0 0 20 20"
          fill="currentColor"
        >
          <path
            fill-rule="evenodd"
            d="M10 18a8 8 0 100-16 8 8 0 000 16zM7 9H5v2h2V9zm8 0h-2v2h2V9zM9 9h2v2H9V9z"
            clip-rule="evenodd"
          />
        </svg>
        <h2 class="text-gray-300 text-2xs">Personal Details</h2>
      </div>
      <div class="flex justify-center items-center space-x-2 text-green-400">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-5 w-5"
          viewBox="0 0 20 20"
          fill="currentColor"
        >
          <path
            d="M8.433 7.418c.155-.103.346-.196.567-.267v1.698a2.305 2.305 0 01-.567-.267C8.07 8.34 8 8.114 8 8c0-.114.07-.34.433-.582zM11 12.849v-1.698c.22.071.412.164.567.267.364.243.433.468.433.582 0 .114-.07.34-.433.582a2.305 2.305 0 01-.567.267z"
          />
          <path
            fill-rule="evenodd"
            d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-13a1 1 0 10-2 0v.092a4.535 4.535 0 00-1.676.662C6.602 6.234 6 7.009 6 8c0 .99.602 1.765 1.324 2.246.48.32 1.054.545 1.676.662v1.941c-.391-.127-.68-.317-.843-.504a1 1 0 10-1.51 1.31c.562.649 1.413 1.076 2.353 1.253V15a1 1 0 102 0v-.092a4.535 4.535 0 001.676-.662C13.398 13.766 14 12.991 14 12c0-.99-.602-1.765-1.324-2.246A4.535 4.535 0 0011 9.092V7.151c.391.127.68.317.843.504a1 1 0 101.511-1.31c-.563-.649-1.413-1.076-2.354-1.253V5z"
            clip-rule="evenodd"
          />
        </svg>
        <h2 class="text-gray-300 text-2xs">Payment</h2>
      </div>
      <div class="flex justify-center items-center space-x-2 text-green-400">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-5 w-5"
          viewBox="0 0 20 20"
          fill="currentColor"
        >
          <path d="M4 4a2 2 0 00-2 2v1h16V6a2 2 0 00-2-2H4z" />
          <path
            fill-rule="evenodd"
            d="M18 9H2v5a2 2 0 002 2h12a2 2 0 002-2V9zM4 13a1 1 0 011-1h1a1 1 0 110 2H5a1 1 0 01-1-1zm5-1a1 1 0 100 2h1a1 1 0 100-2H9z"
            clip-rule="evenodd"
          />
        </svg>
        <h2 class="text-gray-300 text-2xs">ConfirPaymeny</h2>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

