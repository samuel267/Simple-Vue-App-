<template>
  <div>
    <div id="content">
      <Badge></Badge>
      <Badge></Badge>
      <Badge></Badge>
      <Badge></Badge>
      <Badge></Badge>
      <Badge></Badge>
    </div>
    <div id="content2">
<Stamp></Stamp>
<Stamp></Stamp>
<Stamp></Stamp>
<Stamp></Stamp>
<Stamp></Stamp>
<Stamp></Stamp>
    </div>
  </div>
</template>

<script>
import Badge from "./badge.vue";
import Stamp from "./stamp";

export default {
  components: {
    'Badge': Badge,
    'Stamp':Stamp
  }
};
</script>

<style scoped >
#content ,#content2 {
  width: 85%;
  margin: 55px auto;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}
</style>