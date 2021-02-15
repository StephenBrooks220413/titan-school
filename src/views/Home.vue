<template>
  <div class="home">
    <img alt="Vue logo" class="logo" src="../assets/titan.png" />
    <h1 class="display-4">Welcome to Your Education Provider</h1>
    <div class="bg-image intro-img ripple" data-mdb-ripple-color="light">
      <div class="mask" style="background-color: rgba(0, 0, 0, 0.4)">
        <div class="d-flex justify-content-center intro-item h-100">
          <div class="intro-wrapper">
            <h1 class="intro-text">
              Making <br />
              Schools <br />
              Stronger
            </h1>
            <h5 class="content-text text-white">
              Welcome to TITAN — A LINQ Solution. Here, you can learn more about
              how the nation’s fastest-growing school nutrition software
              solutions provider works with districts and schools like yours.
              Together, we are Making Schools Stronger. <br /><br />
            </h5>
          </div>
        </div>
      </div>
      <div class="hover-overlay">
        <div
          class="mask"
          style="background-color: rgba(251, 251, 251, 0.2)"
        ></div>
      </div>
    </div>
  </div>
  <HelloWorld />
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src

@Options({
  components: {
    HelloWorld
  }
})
export default class Home extends Vue {}
</script>

<style lang="scss" scoped>
.logo {
  margin-top: 60px;
  margin-bottom: 60px;
  width: 80%;
  max-height: 600px;
}
.intro-img {
  background: url("../assets/kidsOnBus.png") no-repeat center center fixed;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  margin-bottom: 60px;
  height: 100vh;
  margin-top: 60px;

  .intro-wrapper {
    width: 70%;
    float: right;
    padding-top: 15%;
    padding-right: 20px;
  }
  .intro-text {
    font-size: 4em;
    color: white;
    padding-left: 45%;
  }
  .content-text {
    width: 60%;
    float: right;
  }
}
</style>
