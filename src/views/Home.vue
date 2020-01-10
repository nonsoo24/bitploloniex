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

      <!-- services cards -->
      <div class="row container">
        <div class="column">
          <div class="card border-rounded">
            <a>
              <figure>
                <img src="../assets/img/icon/graph.svg" alt="graph">
              </figure>
              <p class="text-uppercase">Investment archive</p>
            </a>
          </div>
        </div>

        <div class="column">
          <div class="card border-rounded">
            <a>
              <figure>
                <img src="../assets/img/icon/group.svg" alt="graph">
              </figure>
              <p class="text-uppercase">Career</p>
            </a>
          </div>
        </div>

        <div class="column">
          <div class="card border-rounded">
            <a>
              <figure>
                <img src="../assets/img/icon/prize.svg" alt="graph">
              </figure>
              <p class="text-uppercase">Road</p>
            </a>
          </div>
        </div>

        <div class="column">
          <div class="card border-rounded">
            <a>
              <figure>
                <img src="../assets/img/icon/coin.svg" alt="graph">
              </figure>
              <p class="text-uppercase">Analytical Sector</p>
            </a>
          </div>
        </div>
      </div>
          <h5 class="text-uppercase mt-5 text-center">Our Trading Strategy</h5>
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

<style scoped>
* {
  box-sizing: border-box;
}

/* Float four columns side by side */
.column {
  float: left;
  width: 25%;
  padding: 0 20px;
}
.row {margin: -50px 100px;}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Style the counter cards */
.card {
  box-shadow: 0 10px 40px -16px rgba(0,0,0,.4); /* this adds the "card" effect */
  padding: 16px;
  text-align: center;
  background-color: #fff;
  transition: transform 0.3s ease;
  cursor: pointer;
}

/* Responsive columns - one column layout (vertical) on small screens */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
    display: block;
    margin-bottom: 20px;
  }
}

</style>