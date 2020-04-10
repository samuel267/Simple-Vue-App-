<template>
  <div>
    <div id="badge">
      <img src="./concert.jpg" alt="img" />
      <h4>this are the nes that are trending div element has.</h4>
      <p>The div element has no special meaning at all. It represents its children. It can be used with the class.</p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped >
#badge {
  cursor: pointer;
  margin: 20px 0;
  width: 300px;
  height: 280px;
  border-radius: 5px;
  box-shadow: 2px 2px 5px 0;
  padding: 0;
}

#badge img {
  width: 300px;
  height: 180px;
}
#badge h4 {
  text-align: left;
  height: 25px;
  margin: auto 5px;
}

#badge p {
  text-align: left;
  font-size: 14px;
  margin: 15px 5px;
}
</style>