<template>
  <div class="container-me">
       <img class="image" src="~/assets/images/dancingImage.jpg">
    <div class="date">
      <h1 style="font-size: 50px"> {{ $t('headings.saveOurDate') }}</h1>
      <h1 style="font-size: 50px"> {{ $t('headings.date') }}</h1>
    </div>

  </div>
</template>

<script>


</script>

<style>
.container-me {
  overflow: hidden;
  height: inherit;
  display: flex;
  flex-direction: column;
 
  align-items: center;
  text-align: center;
}

.image  {
  height: 70% !important;
 
} 




</style>
