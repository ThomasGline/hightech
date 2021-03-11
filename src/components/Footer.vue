<template>
  <div>
    <link rel="stylesheet" type="text/css" href="Footer.css" />
    <footer>
      <div class="container-fluid">
        <!-- FIRST LINE -->
        <div class="row" id="rowFooter">
          <!-- FIRST column / LOGO-->
          <div class="col-12 col-sm-12 col-lg-4 mb-3">
            <p>HighTech Shop</p>
            <p class="pContact">
              +32 99 98 97 96<br />
              infobe@HighTechShop.be
            </p>
          </div>
          <!-- SECOND column / SUBSCRIBE-->
          <div class="col-12 col-sm-12 col-lg-4 mb-3">
            <h4 id="titleSubscribe">SUBSCRIBE TO US</h4>
            <form class="form-inline my-2 my-lg-0" id="formSubscribe">
              <input
                class="form-control mr-sm-2"
                type="email"
                placeholder="Enter your email..."
              />
              <br />
              <button
                class="btn btn-outline-success my-2 my-sm-0"
                type="submit"
                id="btnSubscribe"
                href="#hightech"
              >
                Subscribe
              </button>
            </form>
            <!-- THIRD column -->
          </div>
          <div class="col-12 col-sm-12 col-lg-4 mb-3">
            <p class="pCentral">
              CENTRAL<br />
              Rue des Volutes, 18<br />
              6030 Charleroi<br />
              +32 99 98 97 96<br />
            </p>
          </div>
        </div>
        <hr />
      </div>
    </footer>
  </div>
</template>