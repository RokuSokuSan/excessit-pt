<template>
<div class="container my-5">
  <!-- Section: Block Content -->
  <section class="dark-grey-text text-center">

    <h3 class="text-center font-weight-bold mb-4 pb-2">Shopping made for you in mind</h3>
    <p class="text-center text-muted w-responsive mx-auto mb-5">Choose your interest of today and pick it.</p>

    <!-- Grid row -->
    <div class="row">

      <!-- Grid column -->
      <div class="col-md-12 mb-4">

        <!-- Card -->
        <div class="card">
          <div class="text-white text-center d-flex align-items-center  py-5 px-4 px-md-5 rounded">
            <div>
              <h6 class="ligthpurple-text">
                <!-- <i class="fas fa-plane"></i> -->
                <strong>EXCESSIT pick n choose</strong>
              </h6>
              <h3 class="py-3 font-weight-bold"><strong>Shopping made for you in mind</strong></h3>
                <carousel />
              
              <p class="pb-3">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Repellat fugiat,
                laboriosam, voluptatem, optio vero odio nam sit officia accusamus minus error nisi architecto
                nulla ipsum dignissimos. Odit sed qui, dolorum!
              </p>
              <a class="btn btn-secondary btn-rounded btn-md"><i class="fas fa-clone left"></i> View project</a>
            </div>
          </div>
        </div>
        <!-- Card -->
      </div>
      <!-- Grid column -->
    </div>
    <!-- Grid row -->

  </section>
  <!-- Section: Block Content -->
</div>
</template>

<script>
import Carousel from './Carousel'

export default {
    name: 'Splash',
    components: {
      Carousel
    }
}
</script>

<style>

</style>