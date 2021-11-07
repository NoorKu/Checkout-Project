<template>
  <div class="w-full h-full">
    <Header />
    <div
      class="flex justify-between space-x-12 bg-gray-100 h-screen px-24 py-10"
    >
      <div
        class="
          flex
          justify-between
          items-center
          space-x-20
          bg-white
          w-2/3
          h-full
          pt-0
          p-10
        "
      >
        <div class="relative mb-12">
          <div
            class="
              flex
              justify-between
              items-center
              space-x-8
              h-3/4
              absolute
              pr-1/2
              -top-20
            "
          >
            <ContentShip />
            <ContentCategory />
          </div>
        </div>
        <div
          class="
            w-10
            h-4
            text-gray-400 text-xl
            absolute
            bottom-40
            left-8
            space-x-4
            px-8
          "
        >
          ...............................................................................................................................................................
        </div>
        <ContentFooter />
      </div>

      <Summary />
    </div>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import ContentShip from "./components/ContentShip.vue";
import ContentCategory from "./components/ContentCategory.vue";
import ContentFooter from "./components/ContentFooter.vue";
import Summary from "./components/Summary.vue";
export default {
  name: "App",
  components: { Header, ContentShip, ContentCategory, ContentFooter, Summary },
};
</script>


