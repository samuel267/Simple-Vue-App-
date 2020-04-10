<template >
  <div>
    <div id="header" v-for="(news) in reports" :key="news">
      <div class="slider">
        <img src="./roya.jpg" alt="img" />
        <h3>{{news.Title}}</h3>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    reports: {
      type: Array,
      required: true
    }
  },
  data() {
    return {};
  },
  methods: {}
};
</script>

<style scooped>
#header {
  display: flex;
  padding: 85px 0 0 0;
  width: 100%;
  height: 480px;
  position: relative;
  justify-content: center;
  }

#header .slider{
  width: 85%;
  height: 470px;
 position: absolute;
 margin: auto;

}

#header .slider img {
  height:460px;
width:100%;
background-image: linear-gradient( rgb(0, 0, 0),rgb(0, 0, 0),rgb(0, 0, 0));
}

#header .slider h3 {
position: absolute;
bottom: 50px;
left: 50px;
color: rgb(255, 255, 255);
width: 90%;
font-size: 33px;
text-align: left;
}
</style>