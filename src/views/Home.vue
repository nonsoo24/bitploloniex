<template>
  <div>
    <!-- navbar -->
    <NavBar />

    <!-- carousel -->
    <section>
      <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <figure>
              <img class="d-block w-100" src="../assets/img/Backgrounds/man-city.jpg" alt="First slide">
            </figure>
          </div>
          <div class="carousel-item">
            <figure>
              <img class="d-block w-100" src="../assets/img/Backgrounds/working.jpg" alt="Second slide">
            </figure>
          </div>
          <div class="carousel-item">
            <figure>
              <img class="d-block w-100" src="../assets/img/Backgrounds/man.jpg" alt="Third slide">
            </figure>
          </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="sr-only">Next</span>
        </a>
      </div>

      <!-- acivities cards -->
      <div class="">
        <div class="card">
          <figure>
            <img src="../assets/img/icon/graph.svg" alt="graph">
          </figure>
          <p class="text-upper">Investment archive</p>
        </div>
        <div class="card">
          <figure>
            <img src="../assets/img/icon/group.svg" alt="graph">
          </figure>
          <p class="text-upper">Investment archive</p>
        </div>
        <div class="card">
          <figure>
            <img src="../assets/img/icon/prize.svg" alt="graph">
          </figure>
          <p class="text-upper">Investment archive</p>
        </div>
        <div class="card">
          <figure>
            <img src="../assets/img/icon/coin.svg" alt="graph">
          </figure>
          <p class="text-upper">Investment archive</p>
        </div>

      </div>
    </section>
  </div>
</template>

<script>
  import NavBar from '@/components/NavBar.vue'

  export default {
    name: 'navbar',
    components: {
      NavBar
    }
  }
</script>
