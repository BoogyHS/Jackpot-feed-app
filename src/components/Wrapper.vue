<template>
  <div class="container">
    <div class="wrapper">
      <div class="daily">
        <img src="../assets/1.png" alt="" />
        <div>
          <img class="box" src="../assets/box.png" alt="" />
          <p class="box-money">1.234$</p>
        </div>
        <div class="timer">
          <span>Must drop in <i class="far fa-clock"></i> 05:45:55</span>
        </div>
      </div>
      <div class="drop">
        <img src="../assets/2.png" alt="" />
        <p>$234,555.90</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Wrapper",
  props: {  },
};
</script>

<style scoped>
.container {
  border: 1px solid;
  width: 20vw;
  max-width: 300px;
  min-width: 150px;
  height: 100vh;
  min-height: 320px;
  background: url("../assets/bg.png");
  background-repeat: no-repeat;
  background-size: cover;
  color: white;
}

.wrapper {
  border: 1px solid white;
  border-radius: 0.5rem;
  width: 90%;
  margin: 4rem auto;
  height: 80%;
}

.daily {
  max-width: 290px;
  min-width: 145px;
  min-height: 35%;
  margin: auto;
  position: relative;
  top: -3.6rem;
}

.daily img {
  margin: auto;
  width: 100%;
  height: auto;
}

.box {
  position: relative;
  top: -1rem;
}

.box-money {
  font-size: 22px;
  position: relative;
  top: -3.5rem;
  margin: auto;
  text-align: center;
}

.timer {
  text-align: center;
  position: relative;
  top: -1rem;
}

.timer span {
  background-color: black;
  padding: 0.2rem 1rem;
  border-radius: 1rem;
  font-family: sans-serif;
  font-size: 0.8rem;
}

.drop {
  border: 1px solid pink;
  max-width: 290px;
  min-width: 145px;
  min-height: 15%;
  background: url("../assets/stars.png");
  background-size: cover;
  display: flex;
  justify-content: space-evenly;
  align-items: center;
}

.drop img {
  width: 35%;
  height: auto;
}

</style>
