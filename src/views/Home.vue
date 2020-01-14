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

      <!-- feature items cards -->
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

      <!-- Trading strategy -->
      <div class="container">
        <h5 class="text-uppercase trading text-center">Our Trading Strategy</h5>
        <ul>
          <li class="">
            <div
              class="strategy-list__item strategy-list__item_bull flex flex-column justify-between width-30 relative">
              Bull<span>To increase</span>
            </div>
          </li>
          <li>
            <div>
              Bear<span>To decrease</span>
            </div>
          </li>
          <li>
            <div>
              Flat<span>Quotation</span>
            </div>
          </li>
        </ul>
      </div>
    </section>

    <section>
      <h3 class="textuppercase">Mission</h3>
      <div class="grid-container">
        <div class="feature-list">
          <h5>SOCIAL POLITICS</h5>
          <p>IMAGE is an indicator of stability, reliability and prosperity, social responsibility for us, which
            increases the credibility of the company.
          </p>
          <div><img src="../assets/img/icon/shield.svg" alt="" class="feature-icon"></div>
        </div>

        <div class="feature-list">
          <h5>QUALIFICATION</h5>
          <p>Our mission is to provide you with training, technology, capital and mentoring so that you become an elite
            trader.
          </p>
          <div><img src="../assets/img/icon/medal.svg" alt="" class="feature-icon"></div>
        </div>

        <div class="feature-list">
          <h5>STABILITY</h5>
          <p>The staff is tripled compared to last year. And it continues to grow.</p>
          <div><img src="../assets/img/icon/check.svg" alt="" class="feature-icon"></div>
        </div>

        <div class="feature-list">
          <h5>ADVERTISING</h5>
          <p>Indicator of exemplary work and responsibility to customers, partners and the state, which is a significant
            reason for an advertising campaign: publications in Internet resources, news feed, etc.
          </p>
          <div><img src="../assets/img/icon/eye.svg" alt="" class="feature-icon"></div>
        </div>

        <div class="feature-list">
          <h5>GROWTH</h5>
          <p>We are not the first in our industry, and therefore our professionals have proven in practice that this
            tool that we use in the market is worthy of being the first in creating business models. We are in the best
            trading positions based on a series of unique algorithms.
          </p>
          <div><img src="../assets/img/icon/arrow-up.svg" alt="" class="feature-icon"></div>
        </div>


        <div class="feature-list">
          <h5>PARTNERS</h5>
          <p>In recent years, the company's net profit has been increasing annually due to the use of special
            strategies, mutual respect and trust.
          </p>
          <div><img src="../assets/img/icon/user.svg" alt="" class="feature-icon"></div>
        </div>
      </div>
      <div class="text-center">
           <button type="button" name="" id="" class="btn btn-primary"> Join</button>
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

<style scoped>
/* fonts */
@font-face {
    font-family: "helvetica-neue-cyr-black";
    src: url("../assets/fonts/HelveticaNeueCyr-Black.otf") format("woff"),
        url("../assets/fonts/HelveticaNeueCyr-Black.otf") format("opentype"),
        url("../assets/fonts/HelveticaNeueCyr-Black.otf") format("truetype");
}

@font-face {
   font-family: "helvetica-neue-cyr-bold";
    src: url("../assets/fonts/HelveticaNeueCyr-Bold.otf") format("woff"),
        url("../assets/fonts/HelveticaNeueCyr-Bold.otf") format("opentype"),
        url("../assets/fonts/HelveticaNeueCyr-Bold.otf") format("truetype");
}

* {
  box-sizing: border-box;
}

/* Float four columns side by side */
.column {
  float: left;
  width: 25%;
  padding: 0 20px;
}

.row {
  margin: -3rem auto;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Style the counter cards */
.card {
  box-shadow: 0 10px 40px -16px rgba(0, 0, 0, .4);
  /* this adds the "card" effect */
  padding: 16px;
  text-align: center;
  background-color: #fff;
  transition: transform 0.3s ease;
  cursor: pointer;
  position: relative;
  margin: 0 2.5%;
}

.trading {
  margin-top: 100px;
}


.card p{
  font-size: 0.8rem;
  font-family: 'helvetica-neue-cyr-bold';
  color: #333333;
}
.card.active::after {
  content: '';
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  height: 1rem;
  background-color: #fdd731
}

.card img {
  transition: filter 1s linear
}

.card:hover {
  transform: translateY(-10%)
}

.card:hover img {
  animation: hue .8s linear infinite
}

.card figure {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 50px
}

.grid-container{
  display: grid;
  grid-template-columns: repeat(3, auto);
  grid-template-rows: repeat(3, auto);
  grid-gap: 3rem;
  margin: 4rem 2rem 0rem 2rem;
}
.feature-list{
  border: 2px #000 solid;
  padding: 2rem 2rem 1rem 4rem
}
.grid-container p {
  font-size: 0.8rem;
  justify-items: start;
  text-align: left;
}

.grid-container h5{
  text-align: left;
  justify-items: start;
  font-size: 1rem;
}

.feature-icon{
  border: 2px #000 solid;
  padding: 1rem;
  width: 65px;
  height: 65px;
  position: relative;
  right: 195px;
  top: -70px;
  border-radius: 50%
  /* transform: translate(-50%,-50%); */
}

.btn-primary{
  border-radius: 100px;
  font-size: 0.875rem;
  padding: 0.4rem 1.4rem;
  background-color: #fdd731;
  border: none
}

.btn-primary:hover{
  color:rgba(0,0,0,.8);
  transform:perspective(1px) translateZ(0);
  box-shadow:0 0 1px transparent;
  background-color: transparent;
}


/* Responsive columns - one column layout (vertical) on small screens */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
    display: block;
    margin-bottom: 20px;
  }

  .row {
    margin: 0px;
  }
}

</style>