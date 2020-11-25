<template>
  <div id="app" class="">
    <div class="container">
      <nav class="navbar navbar-dark bg-dark">
        <a href="#">
          <img width="50px" src="./assets/logo.png" />
        </a>

        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav mr-auto">
            <li class="nav-item active">
              <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Link</a>
            </li>
            <li class="nav-item">
              <a class="nav-link disabled" href="#">Disabled</a>
            </li>
          </ul>
          <form class="form-inline my-2 my-lg-0">
            <input class="form-control mr-sm-2" type="text" placeholder="Username / Email" aria-label="Search">
            <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Login</button>
          </form>
        </div>
      </nav>
    </div>

    <div id="main" class="jumbotron-fluid pt-3 pb-3">
      <div class="container">
        <div class="row">
          <div class="col-12 col-md-7 d-block">
            <h1 class="display-3 text-left">
              Build stunning website and apps
            </h1>

            <p class="lead text-left">
              Meet Cua Socialite. A platform for you and your friends to share and meet online.
            </p>
          </div>
        <div class="col-12 col-md-5"></div>
      </div>
    </div>
    </div>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  // components: {
  //   HelloWorld
  // }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  color: #ffffff;
  background-image: url('./assets/background-image-main.jpg');
}
</style>
