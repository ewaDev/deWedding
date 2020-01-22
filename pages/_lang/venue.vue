<template>
  <div>
    <div class="coverImage"></div>
    <div class="text">
      <p style="font-family: 'Amatic SC', cursive;" >Our wedding is going to take place at Block 33.</p>
    </div>

    <div class="container" style="min-height:0vh;">
      <div class="row">
        <div class="col-md-2"></div>
        <div class="col-md-8" style="text-align:center; ">
          Built in 1907, it was used as a tannery and it has been used as a music venue since 1996. 
The time of the ceremony will be confirmed and announced soon.


          <p style="padding-top: 10px">
            We are very excited to be having our wedding there!
          </p>
        </div>
        <div class="col-md-2"></div>
      </div>
    </div>
    <div style="background-color: #db9797">
      <div class="container" style="min-height:0vh;">
        <div class="row">
          <div class="col-md-2"></div>
          <div class="col-md-8" style="text-align:center; ">
            <h1>Location</h1>
            <p>33 [26 Octovriou], Thessaloniki, 54627</p>
            <p>
              The building is located in the area Sfageia, which is a 15-minute
              car drive from the city centre. There will be free parking at the
              venue and a taxi ride from the city centre would be around €10
            </p>
          </div>
          <div class="col-md-2"></div>
        </div>
      </div>
    </div>
    <div style="text-align:center; padding-bottom: 10px;">
      <h1 style="text-align:center; ">See you there!</h1>
    </div>
  </div>
</template>

<script>
export default {
  computed: {},
  modules: ["bootstrap-vue/nuxt"],
  methods: {}
};
</script>

<style>
@media only screen and (max-width: 1000px) {
  .coverImage {
    display: inline-block;
    width: 100%;
    background-image: url("~assets/images/a.jpg");
    height: 200px !important; /*sorry*/
    background-position: center; /* Center the image */
    background-repeat: no-repeat; /* Do not repeat the image */
    background-size: contain; /* Resize the background image to cover the entire container */
  }
}

.coverImage {
  display: inline-block;
  width: 100%;
  background-image: url("~assets/images/a.jpg");
  height: 50%; /* You must set a specified height */
  background-position: center; /* Center the image */
  background-repeat: no-repeat; /* Do not repeat the image */
  background-size: contain; /* Resize the background image to cover the entire container */
}

.text {
  text-align: center;
  font-size: 3rem;
  
}
</style>
