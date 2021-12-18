<template>
  <div class="home">
    <div class="container">
      <div class="row">
        <div class="col-md-6">
          <div class="d-flex">
            <div class="content justify-content-center">
              <img
                class="img-home"
                src="https://sandbox.jaggs.id/img/jaggs-asset.df4a4001.png"
                alt=""
              />
              <div class="row mt-3">
                <div class="col-8">
                  <div class="input-group input-group-md mb-3">
                    <input
                      type="text"
                      class="form-control"
                      placeholder="BE A GENTLEMEN"
                      aria-label="Cari"
                      aria-describedby="basic-addon1"
                    />
                    <div class="input-group-prepend ml-2">
                      <router-link to="/products">
                        <button
                          class="
                            input-group-text
                            text-white
                            bg-dark
                            border-dark
                            btn btn-sm
                          "
                          id="basic-addon1"
                        >
                          GO
                        </button></router-link
                      >
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
};
</script>

<style>
.home {
  height: 100vh;
  background-image: url("https://sandbox.jaggs.id/img/home-asset.ace58a50.png");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
.content {
  position: absolute;
  top: 200px;
  left: 50px;
}
.img-home {
  width: 50%;
  height: 100%;
}
</style>
