<template>
  <div>
    <navbar></navbar>
    <top-header v-bind:reports="allNewsReport"></top-header>
    <Content></Content>
    <Footer></Footer>
  </div>
</template>

<script>
import Navbar from "./components/navbar.vue";
import Header from "./components/header.vue";
import Content from "./components/content.vue";
import Footer from "./components/footer.vue";

export default {
  components: {
    'navbar': Navbar,
    'top-header': Header,
    'Content':Content,
    'Footer':Footer
  },
  data() {
    return {
      allNewsReport: [
        {
          Title:
            "This is report number two Shorthand property to set values the thickness of the margin area.",
          Content:
            "Information sources refer to place, organization or person where certain information is available.",
          Image: "./concert.jpg",
          Views: 0
        }
      ],
      latest:[],
      trending:[],
      otherRandom:[]
    };
  },
  methods: {},
  computed:{}
};
</script>

<style>
body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  height: auto;
  font-family: Cambria, Cochin, Georgia, Times, "Times New Roman", serif;
}
</style>
