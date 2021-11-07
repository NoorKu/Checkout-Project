<template>
  <div class="space-y-10 w-1/2 flex flex-col justify-center">
    <div class="space-y-4">
      <div class="space-y-0">
        <h2 class="text-2xl text-gray-500">Ship to:</h2>
        <p class="text-lg text-gray-400">Shopping from Indonisia</p>
      </div>

      <select
        class="
          w-80
          h-1/4
          px-4
          py-2
          border-2 border-gray-200
          rounded-sm
          focus:outline-none
        "
      >
        <div
          class="flex flex-col justify-center items-center focus:outline-none"
        >
          <option value="country" class="text-gray-400">Hong Kong</option>
          <option value="country" class="text-gray-400">Paris</option>
          <option value="country" class="text-gray-400">Dubai</option>
        </div>
      </select>
    </div>
    <div class="space-y-4">
      <h2 class="text-xl text-gray-600">Item's retail price:</h2>
      <div class="flex space-x-6">
        <div
          class="
            flex
            justify-center
            items-center
            border-2 border-gray-200
            rounded-sm
            h-5
            w-20
            px-10
            py-4
          "
        >
          <span class="block text-xl text-gray-900">303.99</span>
        </div>
        <div>
          <select
            class="
              w-40
              px-4
              py-1
              border-2 border-gray-200
              rounded-sm
              focus:outline-none
            "
          >
            <div
              class="
                flex flex-col
                justify-center
                items-center
                focus:outline-none
              "
            >
              <option value="country" class="text-gray-400">USD</option>
              <option value="country" class="text-gray-400">EURO</option>
            </div>
          </select>
        </div>
      </div>
    </div>
    <div class="space-y-4">
      <div class="space-y-0 flex items-center space-x-2">
        <h2 class="text-xl text-gray-600">Package Dimenton</h2>
        <span class="text-gray-300">(cm)</span>
      </div>
      <div class="flex justify-center items-center space-x-8">
        <div
          class="
            flex
            justify-center
            items-center
            border-2 border-gray-200
            rounded-sm
            h-10
            w-12
            px-8
            text-xl text-gray-900
          "
        >
          75
        </div>
        <div class="text-gray-300">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-5 w-5"
            viewBox="0 0 20 20"
            fill="currentColor"
          >
            <path
              fill-rule="evenodd"
              d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"
              clip-rule="evenodd"
            />
          </svg>
        </div>
        <div
          class="
            flex
            justify-center
            items-center
            border-2 border-gray-200
            rounded-sm
            h-10
            w-12
            px-8
            text-xl text-gray-900
          "
        >
          45
        </div>
        <div class="text-gray-300">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-5 w-5"
            viewBox="0 0 20 20"
            fill="currentColor"
          >
            <path
              fill-rule="evenodd"
              d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"
              clip-rule="evenodd"
            />
          </svg>
        </div>
        <div
          class="
            flex
            justify-center
            items-center
            border-2 border-gray-200
            rounded-sm
            h-10
            w-12
            px-8
            text-xl text-gray-900
          "
        >
          67
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ContentShip",
};
</script>

