<template>
  <header>
    <div class="header-content">
      <div class="d-flex">
        <img src="img/logo.png" class="logo mx-auto mx-md-0" width="80" />
      </div>
      <div class="nav">
        <a href="#promotion" class="btn text-white">Smart Bounties</a>
        <a href="#smartbounties" class="btn text-white">Get Rewarded</a>
        <a href="https://medium.com/openqdev" class="btn text-white">Blog</a>
      </div>
      <div class="header-text mt-md-0">
        <h1 class="header-title text-white">OpenQ</h1>
        <h2 class="text-white mt-3 mt-md-0">
          Decentralized Job Marketplace <br /><span class="d-none d-md-inline"
            >&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span
          >for Developers
        </h2>
        <div
          class="mt-md-5 pt-md-5 pt-4 d-flex justify-content-center flex-column flex-md-row"
        >
          <a
            href=""
            class="btn btn-lg call-to-action me-md-3"
            >Coming Soon</a
          >
          <!-- <a
            href="#"
            class="btn btn-lg call-to-action call-to-action-invert ms-md-3 mt-3 mt-md-0"
            >Whitepaper</a
          > -->
        </div>
      </div>
    </div>
    <div class="header-dimmer-gradient"></div>
    <div class="rellax" v-rellax="{ speed: 0 }">
      <img src="img/banner-full.png" />
    </div>

    <!--  <div class="rellax" v-rellax="{ speed: 0 }">
      <img src="img/header-layer-clouds.png" />
    </div>
    <div class="rellax" v-rellax="{ speed: 0 }">
      <img src="img/header-layer-mountain2.png" />
    </div>
    <div class="rellax" v-rellax="{ speed: 0 }">
      <img src="img/header-layer-see.png" />
    </div>
    <div class="rellax" v-rellax="{ speed: 0 }">
      <img src="img/header-layer-octo.png" />
    </div>
    <div class="rellax" v-rellax="{ speed: 0 }">
      <img src="img/header-layer-mountain1.png" />
    </div>
    <div class="rellax layer-dev" v-rellax="{ speed: 0 }">
      <img src="img/header-layer-dev.png" />
    </div> -->
  </header>
</template>

<script>
export default {
  name: "Navbar"
};
</script>

<style></style>
