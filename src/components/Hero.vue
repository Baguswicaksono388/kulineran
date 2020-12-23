<template>
  <div class="hero">
    <!-- Desktop -->
    <b-container class="bv-example-row d-none d-md-block">
      <b-row cols-sm="2" cols-md="12">
        <b-col md="5">
          <div class="d-flex h-100">
            <div class="justify-content-center align-self-center">
              <h2>
                <strong>Delicious Food Menu</strong><br />
                in Your Gadget
              </h2>
              <p>Ayo Segera pilih dan pesan makanan favorit anda</p>
              <router-link class="btn btn-lg btn-success" to="/foods">
                <b-icon-arrow-right></b-icon-arrow-right> Pesan
              </router-link>
            </div>
          </div>
        </b-col>
        <b-col md="7" class="mt-4">
          <img src="../assets/image/hero.png" width="100%" />
        </b-col>
      </b-row>
    </b-container>

    <!-- Mobile -->
    <b-container class="bv-example-row d-sm-block d-md-none">
      <b-row cols-sm="2" cols-md="12">
        <b-col md="7" class="mt-4">
          <img src="../assets/image/hero.png" width="110%" />
        </b-col>
        <b-col md="5">
          <div class="d-flex h-100">
            <div class="justify-content-center align-self-center">
              <h2>
                <strong>Delicious Food Menu</strong><br />
                in Your Gadget
              </h2>
              <p>Ayo Segera pilih dan pesan makanan favorit anda</p>
              <router-link class="btn btn-lg btn-success" to="/foods">
                <b-icon-arrow-right></b-icon-arrow-right> Pesan
              </router-link>
            </div>
          </div>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {
  name: "Hero",
};
</script>

<style>
</style>