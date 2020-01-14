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

<!-- features list -->
    <section feature-list>
      <h3 class="text-uppercase text-white pt-5">Mission</h3>
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
           <button type="button" class="btn btn-primary"> Join</button>
        </div>
    </section>

    <!-- statistics -->
    <section>
    <div class="row">
      <div class="col-md-6">
        <dl>
          <dt>2013</dt>
          <dd>Our company has fully adapted to the most popular international markets.</dd>

          <dt>2015</dt>
          <dd>
            Due to the fact that we have a huge experience in bear trading and the experience of crisis trading, our Company successfully earned more than USD 100 million in the Asian market collapse, thereby strengthening its reputation in the domestic market and proving to its partners that the company can earn in any market conditions.
          </dd>

          <dt>2016</dt>
          <dd>
            From the first days the company invested in the extraction of natural resources, precious metals and stones. In 2016, investments in the domestic market of South Africa began to bear serious fruit. BB Sheldon is seriously focused on the development of investments in the gold mining and diamond mining industry in South Africa and is the holder of the largest companies in the country.
          </dd>

          <dt>2019</dt>
          <dd>
            The trading staff, led by Logan Taylor and Robert Palmer, held a closed conference related to the huge promotion of cryptocurrency. Following the results of which it was decided to form a department that will be engaged in the development of crypto trading, monitor and analyze the market. Therefore, we provide an opportunity for private investors to make a profit due to all modern tools, on a par with professional traders. We had a need to create an Internet resource that would give novice investors the opportunity to develop with global traders and achieve maximum success. However, we are professionals in our field, and we do not miss more than one opportunity to increase our own capital and capital of our partners. We follow trends and know how to trade under any market conditions.
        
          </dd>
        </dl>
      </div>
      <div class="col-md-6"></div>
    </div>
    </section>

    <!-- main question -->
    <!-- <section>
      <h5 class="text-uppercase">Main question</h5>
    </section> -->
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

/* feature list */

.grid-container{
  display: grid;
  grid-template-columns: repeat(3, auto);
  grid-template-rows: repeat(3, auto);
  grid-gap: 3rem;
  margin: 4rem 2rem 0rem 2rem;
}
.feature-list{
  border: 2px #fff solid;
  padding: 2rem 2rem 1rem 4rem;
  position: relative;
}
.grid-container p {
  font-size: 0.8rem;
  justify-items: start;
  text-align: left;
  color: #fff;
}

.grid-container h5{
  text-align: left;
  justify-items: start;
  font-size: 1rem;
  color: #fff;
}

.feature-icon{
  border: 2px #fff solid;
  padding: 1rem;
  width: 65px;
  height: 65px;
  position: absolute;
  right: 360px;
  top: 50px;
  border-radius: 50%;
  background-color: #fff
  /* transform: translate(-50%,-50%); */
}

.btn-primary{
  border-radius: 100px;
  font-size: 0.875rem;
  padding: 0.4rem 1.4rem;
  background-color: #fdd731;
  border: none;
  text-transform: uppercase;
  color: #000
}

.btn-primary:hover{
  color:rgba(0,0,0,.8);
  transform:perspective(1px) translateZ(0);
  box-shadow:0 0 1px transparent;
  background-color: transparent;
}

[feature-list]{
  background: url('../assets/img/doc.jpg');
  margin-bottom: 80px;
  padding-bottom: 50px
}

h3{
  font-size: 1.5rem;
}

/* statistics */

dl{
  text-align: left;
  font-family: "Roboto Condensed",sans-serif;
  line-height: 1.7;
  color: rgba(0,0,0,.8);
  font-size: 0.8rem
}

dt{
  color: #FDD731;
  font-size: 1.875rem;
  text-align: left;
  /* font-family: "Roboto Condensed",sans-serif; */
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

  /* feature list */
  .grid-container{
  display: grid;
  grid-template-columns: repeat(1, auto);
  grid-template-rows: repeat(2, auto);
  grid-gap: 1rem;
  margin: 2rem 1rem 1rem 1rem;
}
.feature-list{
  border: 2px #fff solid;
  padding: 2rem 2rem 1rem 4rem;
  position: relative;
}
.grid-container p {
  font-size: 0.8rem;
  justify-items: start;
  text-align: left;
  color: #fff;
}

.grid-container h5{
  text-align: left;
  justify-items: start;
  font-size: 1rem;
  color: #fff;
}

.feature-icon{
  border: 2px #fff solid;
  padding: 1rem;
  width: 65px;
  height: 65px;
  position: absolute;
  right: 330px;
  top: 40px;
  border-radius: 50%;
  background-color: #fff
  /* transform: translate(-50%,-50%); */
}
[feature-list]{
  margin-bottom: 40px;
  padding-bottom: 40px
}


}

</style>