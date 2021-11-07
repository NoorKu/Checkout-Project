<template>
  <div class="w-1/3 h-full items-center">
    <div
      class="
        w-full
        h-full
        flex flex-col
        justify-center
        items-center
        relative
        -top-12
      "
    >
      <div class="bg-white shadow-xl w-5/6 h-auto absolute top-12 pb-2">
        <div class="flex flex-col space-y-2 px-4">
          <h class="text-2xl text-gray-500">Summary</h>
          <p class="text-base text-gray-400">
            The total cost consist of the tax, insurance and the shipping charge
          </p>
          <div
            class="border-b-2 border-gray-300 border-solid space-x-4 pt-4"
          ></div>
        </div>
        <div class="flex flex-col space-y-1 px-4 pt-4">
          <div class="flex justify-between items-center px-2 py-1">
            <span class="text-2xl text-gray-500">Shipping</span>
            <div class="flex justify-center items-center">
              <span class="text-2xl text-gray-700">$</span>
              <span class="text-2xl text-gray-600">59,99</span>
            </div>
          </div>
          <div class="flex justify-between items-center px-2 py-1">
            <span class="text-2xl text-gray-500">Tax</span>
            <div class="flex justify-center items-center">
              <span class="text-2xl text-gray-700">$</span>
              <span class="text-2xl text-gray-700">5 00</span>
            </div>
          </div>
          <div class="flex justify-between items-center px-2 py-1">
            <span class="text-2xl text-gray-500">Insurance</span>
            <div class="flex justify-center items-center">
              <span class="text-2xl text-gray-700">$</span>
              <span class="text-2xl text-gray-600">12 00</span>
            </div>
          </div>
          <div
            class="border-b-2 border-gray-300 border-solid space-x-4 pt-3"
          ></div>
        </div>
        <div class="flex justify-between px-4 pt-4">
          <span class="text-xl text-green-500 underline"
            >How a discount code?</span
          >
          <div class="flex justify-center items-center">
            <span class="text-2xl text-green-500 font-bold">$</span>
            <span class="text-2xl text-green-500 font-bold">59,99</span>
          </div>
        </div>
      </div>
      <div class="bg-white shadow-xl w-5/6 h-auto absolute bottom-2 -mb-6">
        <div class="flex flex-col justify-around space-y-4 p-4">
          <div class="flex justify-between space-x-5">
            <div class="text-gray-400">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-14 w-14"
                viewBox="0 0 20 20"
                fill="currentColor"
              >
                <path d="M4 3a2 2 0 100 4h12a2 2 0 100-4H4z" />
                <path
                  fill-rule="evenodd"
                  d="M3 8h14v7a2 2 0 01-2 2H5a2 2 0 01-2-2V8zm5 3a1 1 0 011-1h2a1 1 0 110 2H9a1 1 0 01-1-1z"
                  clip-rule="evenodd"
                />
              </svg>
            </div>
            <div>
              <h2 class="text-xl text-gray-500">
                Streaming box shipping information
              </h2>
              <p class="text-sm text-gray-400">
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
              </p>
            </div>
          </div>
          <div class="flex justify-between space-x-5">
            <div class="text-gray-400">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-14 w-14"
                viewBox="0 0 20 20"
                fill="currentColor"
              >
                <path
                  fill-rule="evenodd"
                  d="M6 6V5a3 3 0 013-3h2a3 3 0 013 3v1h2a2 2 0 012 2v3.57A22.952 22.952 0 0110 13a22.95 22.95 0 01-8-1.43V8a2 2 0 012-2h2zm2-1a1 1 0 011-1h2a1 1 0 011 1v1H8V5zm1 5a1 1 0 011-1h.01a1 1 0 110 2H10a1 1 0 01-1-1z"
                  clip-rule="evenodd"
                />
                <path
                  d="M2 13.692V16a2 2 0 002 2h12a2 2 0 002-2v-2.308A24.974 24.974 0 0110 15c-2.796 0-5.487-.46-8-1.308z"
                />
              </svg>
            </div>
            <div>
              <h2 class="text-xl text-gray-500">
                Faculty product, money back guarante
              </h2>
              <p class="text-sm text-gray-400">
                Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                Veritatis suscipit, voluptatibus beatae debitis hic assumenda
              </p>
            </div>
          </div>
        </div>
      </div>
      <div
        class="
          flex
          justify-center
          items-center
          p-6
          border-2 border-green-500
          bg-green-500
        "
      ></div>
    </div>
    <div class="flex justify-end items-center mt-4">
      <div
        class="
          w-60
          h-14
          bg-green-500
          border-2 border-solid border-green-500
          rounded-sm
          mb-4
          mr-8
        "
      >
        <div
          class="
            flex
            justify-center
            items-center
            space-x-12
            pt-3
            text-white text-xl
          "
        >
          <span>Next Step</span>
          <span class="block">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-5 w-5"
              viewBox="0 0 20 20"
              fill="currentColor"
            >
              <path
                fill-rule="evenodd"
                d="M12.293 5.293a1 1 0 011.414 0l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-2.293-2.293a1 1 0 010-1.414z"
                clip-rule="evenodd"
              />
            </svg>
          </span>
        </div>
      </div>
    </div>
  </div>
</template> 

<script>
export default {
  name: "Summary",
};
</script>

