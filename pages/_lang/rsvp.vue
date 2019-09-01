<template>
  <div class="container">
  
<form name="contact" method="POST" data-netlify="true">
  <p>
    <p><label>Your Name: <input name="name" type="text" v-model="name"></label> {{name}}
    <p><label>Your Email: <input name="email" type="text" v-model="email"></label>{{email}}
   
  </p>










  
    
      
        <button>Submit</button>
      </form>
    </div>

</template>

<script>
export default {
  data() {
    return {
      name: null,
      email: null
    }
  }
  
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>