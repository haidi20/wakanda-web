<template>
  <div id="nav">
    <nav class="navbar navbar-expand-lg navbar-light">
      <a class="navbar-brand" href="#">
        <img :src="require('@/assets/logo.png')" alt="">
        <p>
          Wakanda
        </p>
      </a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item active">
            <a class="nav-link" href="#">Home</a>
          </li>
          <li class="nav-item ">
            <a class="nav-link" href="#">About Us</a>
          </li>
          <li class="nav-item ">
            <a class="nav-link" href="#">How it works</a>
          </li>
          <li class="nav-item ">
            <a class="nav-link" href="#">For Freelancer</a>
          </li>
          <li class="nav-item ">
            <button class="btn btn-sm btn-get-started">
              Get Started
            </button>
          </li>
        </ul>
      </div>
    </nav>
  </div>
</template>

<script>
  export default {

  }
</script>

<style lang="scss" scoped>
  $text-red: #FE5756;

  nav {
    padding-left: 5rem;
    padding-right: 5rem;

    a{

      p {
        display: inline-block;
        font-weight: bold;
      }
    }
  }

  ul.navbar-nav li {
    padding-left: 1rem;

    .nav-link {
      font-size: 16px;
      color: #797979;

      &.active {
        color: $text-red !important;
        font-weight: 600;
      }

      &.hover {
        color: $text-red !important;
      }
    }
  }

  .btn-get-started {
    color: white;
    background-color: #166BAC;
  }
</style>
