<template>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
        <div class="square">
          <div class="card text-center">
            <div class="card-header">
              Web <span>Development Portfolio</span> of ...
            </div>
            <div class="card-body">
              <h5 class="card-title">Zimasile W Ngcukana</h5>
              <img class="me" src="https://i.postimg.cc/5t4tX787/IMG-20221028-103838.jpg" width="350" alt="me">
              <p class="card-text">...hi there, welcome to my portfolio. I am an upcoming and aspiring developer working towards being a full stack developer, feel free to browse trough and please contact me when you are interested in my services, thank you in advance.</p>
            </div>
            <div class="card-footer text-muted">
              "I'm the greatest, I said it before I knew I was."
            </div>
          </div>
        </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
<style>
.square {
  display: flex;
  color: black;
  margin-top: 30px;
}
span {
  color: purple;
}
p{
  margin-top: 70px;
}

</style>
