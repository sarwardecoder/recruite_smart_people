<template>
  <div class="about">
    <img alt="JRF logo" class="logo" src="@/assets/JRF_services.png" width="550" height="110" />
    
    <br>
    <h1>About <span class="blue">Our Services</span></h1>
    <br>
    <br>
    
      <p><span class="blue">JRF Recruit</span> is a strong wing of JRF Intelligent Co. Ltd, specializing in professional, trustworthy, and experienced job recruitment. With a robust ecosystem, we seamlessly connect top talent with the right opportunities, empowering businesses and job seekers alike.</p>
    <!-- <h2>Company Details</h2> -->
    
    <img alt="JRF Office Image" class="image" src="@/assets/JRF_office1.png" width="400" height="300" /> <br>
    <div class="mid-section">
      Connecting you with the right talent is our expertise. At <span class="blue">JRF Recruit</span>, we understand the importance of a team that fits your business goals. Whether it’s short-term assistance or long-term engagement, we tailor our services to meet your specific hiring demands. Our commitment is not just to fill a position but to foster a long-term partnership that contributes to your success.
  
    </div>
    <br>
    
    <div class="parallel">
      <div class="mission-vision"> <h2>Our Mission</h2>
      Connecting talent with opportunity — we pave the way for professional growth and business success.
    </div>
    <div class="mission-vision vision"><h2>Our Vision</h2>
      Redefining recruitment to be the standard of excellence, we aspire to be at the heart of career advancement globally.
    </div>
    </div>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
  }
}
div{
  margin: 5px;

}
.image{
  border-radius: 15px;
}
.blue{
  margin: 2px;
  background-color: rgb(43, 104, 209);

  color: aliceblue;
  padding: 5px;
  /* border-radius: 5%; */
  
}
.parallel{
  display: flex;
  /* background-color:  rgb(122, 168, 249); */
}
.parallel h2{
  font-weight: bolder;
  padding: 2px;
  margin: 3px;
}
.vision{
  background-color: rgb(121, 165, 241);
  margin: 3px;
  padding: 15px;
  border-radius: 15px;

}
</style>
