<script setup>
defineProps({
  msg: {
    type: String,
    required: true,
  },
})
</script>

<template>
  <div class="pre_header">
    <img src="https://media.istockphoto.com/id/1384702181/photo/young-businessperson-facilitating-a-meeting.webp?s=2048x2048&w=is&k=20&c=F5y3u0gXjEhnilq-6k1Q4M9turaaLvCtyeef2yDNEtU=" alt="Human Resources">
  </div>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h3>
      with JRF Recruitment
      
    </h3>
  </div>
</template>

<style scoped>
.pre_header img{

height: 100%;
width: 110%;
border-radius: 15px;
}
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}
.greetings{

}
.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h2,
  .greetings h3 {
    text-align: left;
  }
}
</style>
