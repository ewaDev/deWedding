<template>

    <!--codecraft start-->
    <nav class="navbar navbar-light navbar-expand-lg">
        <nuxt-link to="/" class="navbar-brand">{{ $t('navbar.home') }}</nuxt-link>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse"  id="navbarSupportedContent">
            <ul class="navbar-nav ml-auto "  style="text-align: center" >
                <li class="nav-item" data-toggle="collapse" data-target=".navbar-collapse.show">
                  <nuxt-link to="/travel" class="nav-link">  {{ $t('navbar.travel') }}</nuxt-link>
                </li>
                <li class="nav-item" data-toggle="collapse" data-target=".navbar-collapse.show">
                    <nuxt-link to="/rsvp" class="nav-link">{{ $t('navbar.rsvp') }}</nuxt-link>
                </li>    
                <li class="nav-item" data-toggle="collapse" data-target=".navbar-collapse.show">
                  <nuxt-link to="/venue" class="nav-link"> {{ $t('navbar.venue') }}</nuxt-link>
                </li>
                <!-- <li class="flagbutton" data-toggle="collapse" data-target=".navbar-collapse.show">
                  <div class="flag-icon flag-icon-gb flag"  @click="changeLanguage('en')"></div>
                </li>
                <li class="flagbutton" data-toggle="collapse" data-target=".navbar-collapse.show"> 
                   <div class="flag-icon flag-icon-gr flag" @click="changeLanguage('gr')"></div>
                </li> -->
            </ul>   
        </div>
    </nav>
  
  
</template>

<script>
export default {
    computed: {
    title() {
      // this.$t("title") returns the value of our title attribute in our JSON file
      // The correct file is selected based on the locale value
      // If it was an object, we could access its attributes like so: this.$t("myObject").myAttribute
      return this.$t("title");
    }
  },
  modules : ['bootstrap-vue/nuxt'],
  methods: {
    /**
     * Called when a language button is clicked
     * Changes the i18n context variable's locale to the one selected
     */
    changeLanguage(lang) {  
      this.$i18n.locale = lang;
    }
  }
    
}
</script>
<style >
</style>