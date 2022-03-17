<template>
  <div>
    <div class="main-content">
      <!-- Header (v8) -->
      <section
        class="slice slice-xl bg-cover bg-size--cover"
        data-offset-top="#header-main"
        style="
          background: #0000ff;
          background-position: center 30%;
          background-repeat: no-repeat;
          background-size: auto;
        "
      >
        <span class="mask bg-gradient-primary opacity-6"></span>
        <div class="container-fluid py-6 py-lg-9">
          <div class="row">
            <div class="col-lg-12">
              <div class="text-center">
                <h4
                  class="text-white text-uppercase font-weight-400 mb-0"
                  style="font-family: 'Oswald', sans-serif"
                >
                  Tobi lou wants to Perish Non-Perishable? We say nah.
                </h4>
                <h2
                  class="
                    display-1
                    font-weight-600
                    text-white text-uppercase
                    mb-2
                  "
                  style="font-family: 'Oswald', sans-serif"
                >
                  F*ck Tobi Lou
                </h2>
                <div class="mt-4">
                  <a
                    href="#"
                    class="btn btn-white rounded text-uppercase"
                    style="font-family: 'Oswald', sans-serif; line-height: 2.2"
                    >Download the album!</a
                  >
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <section class="slice slice-lg">
        <div class="container">
          <div class="row row-grid justify-content-around align-items-center">
            <div class="col-lg-5">
              <div class="">
                <h5
                  class="text-uppercase"
                  style="font-family: 'Oswald', sans-serif"
                >
                  Endorsed by tobi lou himself!
                </h5>
                <!-- <p class="lead my-4">
                  With Purpose you get components and examples, including tons
                  of variables that will help you customize this theme with
                  ease.
                </p> -->
                <!-- <ul class="list-unstyled">
                  <li class="py-2">
                    <div class="d-flex align-items-center">
                      <div>
                        <div
                          class="
                            icon icon-shape icon-primary icon-sm
                            rounded-circle
                            mr-3
                          "
                        >
                          <i class="fas fa-store-alt"></i>
                        </div>
                      </div>
                      <div>
                        <span class="h6 mb-0">Perfect for modern startups</span>
                      </div>
                    </div>
                  </li>
                  <li class="py-2">
                    <div class="d-flex align-items-center">
                      <div>
                        <div
                          class="
                            icon icon-shape icon-warning icon-sm
                            rounded-circle
                            mr-3
                          "
                        >
                          <i class="fas fa-palette"></i>
                        </div>
                      </div>
                      <div>
                        <span class="h6 mb-0"
                          >Built with customization and ease-of-use at its
                          core</span
                        >
                      </div>
                    </div>
                  </li>
                  <li class="py-2">
                    <div class="d-flex align-items-center">
                      <div>
                        <div
                          class="
                            icon icon-shape icon-success icon-sm
                            rounded-circle
                            mr-3
                          "
                        >
                          <i class="fas fa-cog"></i>
                        </div>
                      </div>
                      <div>
                        <span class="h6 mb-0"
                          >Quality design and thoughfully crafted code</span
                        >
                      </div>
                    </div>
                  </li>
                </ul> -->
              </div>
            </div>
            <div class="col-lg-6">
              <img
                alt="Image placeholder"
                src="./assets/heytobi.png"
                class="img-fluid img-center"
              />
            </div>
          </div>
        </div>
      </section>
      <!-- Features (v19) -->
      <section
        class="slice slice-lg bg-bg-primary bg-cover bg-size--cover"
        style="background: #0000ff"
      >
        <span class="mask bg-primary opacity-7"></span>
        <div class="container">
          <div class="row row-grid">
            <div class="col-lg-6">
              <div class="card mb-4">
                <div class="card-body">
                  <div class="row">
                    <div class="col-md-2">
                      <img
                        class="song-img"
                        src="./assets/img/hopeless.png"
                        alt=""
                      />
                    </div>
                    <div class="col-md-10 text-center text-md-left">
                      <h3 class="h5 mb-0">Hopeless Romantic</h3>
                      <p class="mb-0">
                        <audio controls>
                          <source
                            src="./assets/mp3/hopeless.mp3"
                            type="audio/mpeg"
                          />
                        </audio>
                      </p>
                      <!-- <a href="#" @click="downloadResource('./assets/mp3/hopeless.mp3')"  class="font-weight-bold">Download Now!</a> -->
                    </div>
                  </div>
                </div>
              </div>
              <div class="card mb-4">
                <div class="card-body">
                  <div class="row">
                    <div class="col-md-2">
                      <img
                        class="song-img"
                        src="./assets/img/baby.png"
                        alt=""
                      />
                    </div>
                    <div class="col-md-10 text-center text-md-left">
                      <h3 class="h5 mb-0">Babycakes</h3>
                      <p class="mb-0">
                        <audio controls>
                          <source
                            src="./assets/mp3/babycakes.mp3"
                            type="audio/mpeg"
                          />
                        </audio>
                      </p>
                      <!-- <a href="#" @click="downloadResource('./assets/mp3/hopeless.mp3')"  class="font-weight-bold">Download Now!</a> -->
                    </div>
                  </div>
                </div>
              </div>
              <div class="card mb-4">
                <div class="card-body">
                  <div class="row">
                    <div class="col-md-2">
                      <img
                        class="song-img"
                        src="./assets/img/meaningless.png"
                        alt=""
                      />
                    </div>
                    <div class="col-md-10 text-center text-md-left">
                      <h3 class="h5 mb-0">Meaningless</h3>
                      <p class="mb-0">
                        <audio controls>
                          <source
                            src="./assets/mp3/meaningless.mp3"
                            type="audio/mpeg"
                          />
                        </audio>
                      </p>
                      <!-- <a href="#" @click="downloadResource('./assets/mp3/hopeless.mp3')"  class="font-weight-bold">Download Now!</a> -->
                    </div>
                  </div>
                </div>
              </div>
              <div class="card mb-4">
                <div class="card-body">
                <div class="row">
                  <div class="col-md-2">
                     <img class="song-img" src="./assets/img/2.png" alt="">
                  </div>
                  <div class="col-md-10 text-center text-md-left">
                    <h3 class="h5 mb-0">2hrs+</h3>
                    <p class="mb-0">
                      <audio controls>
                        <source src="./assets/mp3/2.mp3" type="audio/mpeg">
                      </audio>
                    </p>
                    <!-- <a href="#" @click="downloadResource('./assets/mp3/hopeless.mp3')"  class="font-weight-bold">Download Now!</a> -->
                  </div>
                </div>
                </div>
              </div>
                  <div class="card mb-4">
                <div class="card-body">
                <div class="row">
                  <div class="col-md-2">
                     <img class="song-img" src="./assets/img/wide.png" alt="">
                  </div>
                  <div class="col-md-10 text-center text-md-left">
                    <h3 class="h5 mb-0">WIDE OPEN</h3>
                    <p class="mb-0">
                      <audio controls>
                        <source src="./assets/mp3/wide.mp3" type="audio/mpeg">
                      </audio>
                    </p>
                    <!-- <a href="#" @click="downloadResource('./assets/mp3/hopeless.mp3')"  class="font-weight-bold">Download Now!</a> -->
                  </div>
                </div>
                </div>
              </div>
                  <div class="card mb-4">
                <div class="card-body">
                <div class="row">
                  <div class="col-md-2">
                     <img class="song-img" src="./assets/img/jelly.png" alt="">
                  </div>
                  <div class="col-md-10 text-center text-md-left">
                    <h3 class="h5 mb-0">Jelly</h3>
                    <p class="mb-0">
                      <audio controls>
                        <source src="./assets/mp3/jelly.mp3" type="audio/mpeg">
                      </audio>
                    </p>
                    <!-- <a href="#" @click="downloadResource('./assets/mp3/hopeless.mp3')"  class="font-weight-bold">Download Now!</a> -->
                  </div>
                </div>
                </div>
              </div>
            </div>
            <div class="col-lg-6">
              <div class="card mb-4">
                <div class="card-body">
                                 <div class="row">
                  <div class="col-md-2">
                     <img class="song-img" src="./assets/img/yamaguchi.png" alt="">
                  </div>
                  <div class="col-md-10 text-center text-md-left">
                    <h3 class="h5 mb-0">Yamaguchi</h3>
                    <p class="mb-0">
                      <audio controls>
                        <source src="./assets/mp3/yamaguchi.mp3" type="audio/mpeg">
                      </audio>
                    </p>
                    <!-- <a href="#" @click="downloadResource('./assets/mp3/hopeless.mp3')"  class="font-weight-bold">Download Now!</a> -->
                  </div>
                </div>
                </div>
              </div>
              <div class="card mb-4">
                <div class="card-body">
                                 <div class="row">
                  <div class="col-md-2">
                     <img class="song-img" src="./assets/img/she.png" alt="">
                  </div>
                  <div class="col-md-10 text-center text-md-left">
                    <h3 class="h5 mb-0">She Know My Name</h3>
                    <p class="mb-0">
                      <audio controls>
                        <source src="./assets/mp3/she.mp3" type="audio/mpeg">
                      </audio>
                    </p>
                    <!-- <a href="#" @click="downloadResource('./assets/mp3/hopeless.mp3')"  class="font-weight-bold">Download Now!</a> -->
                  </div>
                </div>
                </div>
              </div>
              <div class="card mb-4">
                <div class="card-body">
                                                   <div class="row">
                  <div class="col-md-2">
                     <img class="song-img" src="./assets/img/hurry.png" alt="">
                  </div>
                  <div class="col-md-10 text-center text-md-left">
                    <h3 class="h5 mb-0">Hurry-Up Offense</h3>
                    <p class="mb-0">
                      <audio controls>
                        <source src="./assets/mp3/hurry.mp3" type="audio/mpeg">
                      </audio>
                    </p>
                    <!-- <a href="#" @click="downloadResource('./assets/mp3/hopeless.mp3')"  class="font-weight-bold">Download Now!</a> -->
                  </div>
                </div>
                </div>
              </div>
              <div class="card mb-4">
                <div class="card-body">
                                                   <div class="row">
                  <div class="col-md-2">
                     <img class="song-img" src="./assets/img/busy.png" alt="">
                  </div>
                  <div class="col-md-10 text-center text-md-left">
                    <h3 class="h5 mb-0">Busy</h3>
                    <p class="mb-0">
                      <audio controls>
                        <source src="./assets/mp3/busy.mp3" type="audio/mpeg">
                      </audio>
                    </p>
                    <!-- <a href="#" @click="downloadResource('./assets/mp3/hopeless.mp3')"  class="font-weight-bold">Download Now!</a> -->
                  </div>
                </div>
                </div>
              </div>
              <div class="card mb-4">
                <div class="card-body">
                                                   <div class="row">
                  <div class="col-md-2">
                     <img class="song-img" src="./assets/img/last.png" alt="">
                  </div>
                  <div class="col-md-10 text-center text-md-left">
                    <h3 class="h5 mb-0">The Last Dance</h3>
                    <p class="mb-0">
                      <audio controls>
                        <source src="./assets/mp3/last.mp3" type="audio/mpeg">
                      </audio>
                    </p>
                    <!-- <a href="#" @click="downloadResource('./assets/mp3/hopeless.mp3')"  class="font-weight-bold">Download Now!</a> -->
                  </div>
                </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </div>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: "App",
  components: {
    // HelloWorld
  },

  methods: {
    downloadBlob: function (blob, filename) {
      var a = document.createElement("a");
      a.download = filename;
      a.href = blob;
      document.body.appendChild(a);
      a.click();
      a.remove();
    },

    downloadResource: function (url) {
      var filename = url.split("\\").pop().split("/").pop();
      fetch(url, {
        mode: "no-cors",
      })
        .then((response) => response.blob())
        .then((blob) => {
          let blobUrl = window.URL.createObjectURL(blob);
          this.downloadBlob(blobUrl, filename);
        })
        .catch((e) => console.error(e));
    },
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.song-img {
  width: 100%;
  height: auto;
  margin-bottom: auto;
}

.main-content {
  margin-top: -62px;
}
</style>
