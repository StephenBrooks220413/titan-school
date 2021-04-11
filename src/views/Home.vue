<template>
  <div class="home">
    <div class="intro-bg"></div>
    <div class="bg-image intro-img ripple" data-mdb-ripple-color="light">
      <div class="mask" style="background-color: rgba(0, 0, 0, 0.4)">
        <div class="d-flex justify-content-center intro-item h-100">
          <div class="intro-wrapper">
            <h1 class="intro-text">
              Making <br />
              Online <br />
              Stronger
            </h1>
            <h5 class="content-text text-white">
              Welcome to Steven's Web Solutions. Here, you can learn more about
              how the nation’s fastest-growing technological software solutions
              provide small businesses with affordable and manageable websites.
              Together, we are Making Websites Stronger. <br /><br />
              <a
                href="mailto:stephenbrooks714@gmail.com"
                class="btn btn-danger btn-lg"
                >MORE INFO</a
              >
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
.intro-bg {
  background: url("../assets/logo1.png") no-repeat center center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  height: 100vh;
  width: 100%;
  margin-bottom: 40px;
}
.logo {
  margin-top: 60px;
  margin-bottom: 60px;
  width: 80%;
  max-height: 600px;
}
.intro-img {
  background: url("https://images.unsplash.com/photo-1542744094-3a31f272c490?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80")
    no-repeat center center fixed;
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
