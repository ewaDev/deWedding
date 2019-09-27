<template>
<header class="header">
    
    <nuxt-link to="/" class="logo">Home</nuxt-link>
     <!-- <input class="menu-btn" type="checkbox" id="menu-btn" />
     <label class="menu-icon" for="menu-btn"><span class="navicon"></span></label> -->
    <nav>
        <ul class="menu">
            <li><nuxt-link to="/aboutus" class="navlink">AboutUs</nuxt-link></li>
            <li><nuxt-link to="/rsvp" class="navlink">RSVP</nuxt-link></li>
            <li><nuxt-link to="/venue" class="navlink">Venue</nuxt-link></li>
            <li><button @click="changeLanguage('en')">EN</button></li>
            <li><button @click="changeLanguage('gr')">GR</button></li>
        </ul>
    </nav>
</header>
    
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