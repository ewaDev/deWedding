<template>
<header class="header">
    
    <nuxt-link to="/" class="logo">Home</nuxt-link>
     <input class="menu-btn" type="checkbox" id="menu-btn" />
     <label class="menu-icon" for="menu-btn"><span class="navicon"></span></label>
    <nav>
        <ul class="menu">
            <li><nuxt-link to="/aboutus" class="navlink">AboutUs</nuxt-link></li>
            <li><nuxt-link to="/rsvp" class="navlink">RSVP</nuxt-link></li>
            <li><nuxt-link to="/venue" class="navlink">Venue</nuxt-link></li>
        </ul>
    </nav>
</header>
    
</template>

<script>
export default {
    
}
</script>

<style >

</style>