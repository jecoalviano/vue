<template>
    
   <!--Content here-->
<div class="contact">
<Nav />
<div class="container">
    <div class="row justify-content-center">
        <div class="col-10 col-md-6">
            <h1 class="contact-us-text mt-5">Contact Us</h1>
            <hr class="solid mt-0">

            <form>
                <div class="form-group">
                    <label>Firstname *</label>
                    <input type="email" class="form-control" aria-describedby="emailHelp" placeholder="Please fill your firstname *">
                  </div>
                <div class="form-group">
                  <label>Email *</label>
                  <input type="email" class="form-control" aria-describedby="emailHelp" placeholder="Please fill your email * ">
                </div>
                <div class="form-group">
                  <label>Message *</label>
                  <input type="password" class="form-control" placeholder="Message for me *">
                </div>
             
            <div class="form-group ml-4">
                <input class="form-check-input" type="checkbox" value="" id="personal" checked>
                <label class="form-check-label ml-n2" for="personal">* I agree to allow Example Company to store and process my personal data.</label>
            </div>
            <div class="form-group ml-4">
                <input class="form-check-input" type="checkbox" value="" id="marketing">
                <label class="form-check-label ml-n2" for="marketing">* I agree to receive marketing communications from Example Company.</label>
            </div>
            <button class="btn btn-primary mt-3 mb-1">Send Messages</button>
            <p class="text-muted mb-5"> <strong>*</strong>These fields are required</p>
        </form>
        </div>
    </div>
  <!--Content Close-->
</div>
<Footer />
</div>
</template>


<script>

import Nav from '@/components/Nav.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'Contact',
  components: {
    //HelloWorld
    Nav,
    Footer,
  }
}
</script>