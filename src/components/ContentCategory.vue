<template>
  <div class="space-y-10 flex flex-col justify-center items-center">
    <div class="space-y-4">
      <div>
        <h2 class="text-2xl text-gray-500">Category:</h2>
        <p class="text-lg text-gray-400">Used to compute taxi & duits</p>
      </div>

      <select class="w-80 h-1/4 px-4 py-2 border-2 border-gray-200 rounded-sm">
        <div
          class="flex flex-col justify-center items-center focus:outline-none"
        >
          <option value="country" class="text-gray-400">Famiture</option>
          <option value="country" class="text-gray-400">Chocolate</option>
        </div>
      </select>
    </div>
    <div class="space-y-4">
      <h2 class="text-xl text-gray-600">Taxis & Duits payed by:</h2>
      <div class="flex space-x-6">
        <div
          class="
            flex
            justify-center
            items-center
            border-2 border-green-500
            rounded-sm
            h-5
            w-1/2
            px-10
            py-4
          "
        >
          <span class="block text-xl text-green-500 font-medium">Sender</span>
        </div>
        <div
          class="
            flex
            justify-center
            items-center
            border-2 border-gray-300
            rounded-sm
            h-5
            w-1/2
            px-10
            py-4
          "
        >
          <span class="block text-xl text-gray-600 font-medium">Receiver</span>
        </div>
      </div>
    </div>
    <div class="space-y-4">
      <h2 class="text-xl text-gray-600">Package Weight</h2>

      <div class="flex space-x-6">
        <div class="flex space-x-6">
          <div
            class="
              relative
              flex
              items-center
              border-2 border-gray-300
              rounded-sm
              h-10
              w-60
              px-10
              py-4
            "
          >
            <span class="block text-xl text-right absolute left-4 text-gray-900"
              >3.6</span
            >
          </div>
        </div>
        <span class="block text-xl text-gray-400">Kg</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ContentCategory",
};
</script>
