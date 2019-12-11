<template>
  <div>
    <div class="coverImageTravel"></div>
    <div class="text" style="padding-top: 0px">
      <p>Hello and welcome to Thessaloniki!</p>
    </div>

    <div class="container" style="min-height:0vh; padding-bottom: 20px">
      <div class="row">
        <div class="col-md-2"></div>
        <div class="col-md-8" style="text-align:center; ">
          Thessaloniki is the second largest city in Greece after Athens – and
          in our opinion the most beautiful city in Greece! We hope you enjoy
          your stay in Thessaloniki and that you get a chance to walk around the
          city, visit the museums, eat delicious food and enjoy the view of the
          sea. On this page we will try to give you a few suggestions about
          places that you could visit in Thessaloniki, restaurants, bars as well
          as recommend areas that are nice to stay in the city.
        </div>
        <div class="col-md-2"></div>
      </div>
    </div>

    <div class="jumbotron" style="text-align:center; padding-top:0">
      <div class="row" style="text-align:center; padding: 15px;">
        <div class="col-md-12">
          <h1>How to get to Thessaloniki (SKG) by plane</h1>
        </div>
        <div class="row" style="padding-top:15px">
          <div class="col-md-3"> </div>
          <div class="col-md-3">
            <h2>From Scotland</h2>
            <p>
              Aegean Airlines: fly from Edinburgh to Thessaloniki via Athens
              (connecting flight)
            </p>
            <p>
              Easy Jet: fly from Edinburgh to Athens and book a separate flight
              from Athens to Thessaloniki
            </p>
          </div>
          <div class="col-md-3">
            <h2>From England</h2>
            <p>
              Fly from Manchester to Thessaloniki with a direct flight (plenty
              of airlines to choose from including Easy Jet, Jet2, Ryanair)
            </p>
            <p>
              Fly from London to Thessaloniki with a direct flight (plenty of
              airlines to choose from including Aegean airlines, Easy Jet, Jet2,
              Ryanair)
            </p>
          </div>
           <div class="col-md-3"></div>
        </div>
      </div>
    </div>
    <div style="text-align:center; padding-bottom: 10px;">
      <h1 style="text-align:center; ">Where to Stay</h1>
      <p>We think that the best areas to stay in the city are: 
        <ul style="list-style-type:none">
        <li>City centre </li>
        <li>Ano Poli  </li>
        <li> 40 ekklissies </li>
        <li>Kalamaria</li>
        </ul>

<p>The city centre would be the most convenient place to stay. A hotel or an Airbnb
would be fine choices. The city has public buses and taxis are relatively cheap.
</p>
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
  .coverImageTravel {
    display: inline-block;
    width: 100%;
    background-image: url("~assets/images/Travel.jpg");
    height: 200px !important; /*sorry*/
    background-position: center; /* Center the image */
    background-repeat: no-repeat; /* Do not repeat the image */
    background-size: contain; /* Resize the background image to cover the entire container */
  }
}

.coverImageTravel {
  display: inline-block;
  width: 100%;
  background-image: url("~assets/images/Travel.jpg");
  height: 50%; /* You must set a specified height */
  background-position: center; /* Center the image */
  background-repeat: no-repeat; /* Do not repeat the image */
  background-size: contain; /* Resize the background image to cover the entire container */
}

.text {
  text-align: center;
  font-size: 2.5rem;
  font-family: "Josefin Slab", serif;
}
</style>
