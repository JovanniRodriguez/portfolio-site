<template>
  <div class="container-fluid" style="height: 100vh; ">
    <div class="row h-100">
      
      <!--start carousel component-->
      <div class="col h-100" id="left-carousel-col">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nesciunt nostrum sapiente natus quas fuga labore voluptatum at eos qui delectus?</div>
      <!--end carousel component-->

      <!--start info col-->
      <div class="col d-flex h-100 justify-content-center
      align-items-center text-center" id="right-info-col">
        
        <div class="row">
          <div class="col m-5">
            <h1>Jovani Rodriguez</h1>
          </div>
          <div class="row">
            <div class="col">
              <img class="headshot-img" src="/images/headshot-cap-gown.jpg" alt="">
            </div>
          </div>
          <div class="row d-flex mt-5
          justify-content-center">
              <img class="contact-icon" src="/icons/resume-icon.png" alt="">
            
              <img class="contact-icon" src="/icons/mail-icon.png" alt="">
            
            
              <img class="contact-icon" src="/icons/linkedin-icon.png" alt="">
            
            
              <img class="contact-icon" src="/icons/github-icon.png" alt="">
            
          </div>
        </div>
      </div>
      
      <!--end info col-->

    </div>
  </div>  
</template>

<script>
export default {
  name: 'Home',

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#right-info-col {
  background-color: black;
  color: white;
}
.headshot-img {
  width: 500px;
  border-radius: 12px;
}
.contact-icon {
  width: 80px !important;
  cursor: pointer;
}
.contact-icon:hover{
  transform: scale(1.3);
  transition: transform 0.5s ease;
}
</style>
