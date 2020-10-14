<template>

<div class="home">
  <Nav/>
  <!--Content here-->
    <div class="container">
       <!--Banner-->
       <div class="row">
         <img src="images/background.jpeg" alt="" class="img-fluid">
       </div>
       <!--Banner Close-->
       
    <!--Tulisan-->
    <div class="row my-5">
      <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus similique laborum eligendi voluptatum nulla delectus quam facilis nostrum tenetur voluptates esse magnam non, optio explicabo ex quibusdam? Sit, architecto eos?</p>
      <p class="mt-2">Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus similique laborum eligendi voluptatum nulla delectus quam facilis nostrum tenetur voluptates esse magnam non, optio explicabo ex quibusdam? Sit, architecto eos?</p>

    </div>
    <!--Tulisan Close-->

    <!--Card-->

    <div class="row">
      <div class="col-md-4 mb-2"> <!--md = medium-->
        <div class="card">
          <div class="card-body text-center">
            <h3 class="my-2">First</h3> <!--margin y untuk atas dan bawah-->
              <span class="subtitle">FIRST</span>
              <p class="card-text text-left my-2">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            </div>
        </div>
      </div>


      <div class="col-md-4 mb-2"> 
        <div class="card">
          <div class="card-body text-center">
            <h3 class="my-2">Second</h3>
            <span class="subtitle">SECOND</span>
            <p class="card-text text-left my-2">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
          </div>
        </div>
      </div>


      <div class="col-md-4 mb-2">
        <div class="card">
          <div class="card-body text-center">
            <h3 class="my-2">Third</h3>
              <span class="subtitle">THIRD</span>
              <p class="card-text text-left my-2">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            </div>
        </div>
      </div>
    </div>
    <!--Card Close-->

    <!--Subscribe-->
  <div class="row">
    <div class="col-12 text-center">
      <h3 class="subtitle mt-4">Be the first to know</h3>
      <p>Subscribe to receive the updates on our new lauches, articles, and exclusive previews</p>
      <div class="input-group mb-3 d-inline-flex justify-content-center col-md-4 mb-3">
        <input type="text" class="form-control subscribe text-subscribe" placeholder="Enter your email address" aria-label="Email" aria-describedby="basic-addon2">
        <div class="input-group-append">
          <button class="input-group-text subscribe-button text-subscribe" id="basic-addon2">Subscribe</button>
        </div>
      </div>
    </div>
  </div>
  <!--Subscribe Close-->

  <!--Content Close-->
</div>
<Footer/>
</div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Nav from '@/components/Nav.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'Home',
  components: {
    //HelloWorld
    Nav,
    Footer,
  }
}
</script>
