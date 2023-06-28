<template>
<main>
        <div class="container-fluid text-center">
          <div>
            <h1 class="text-decoration-underline">MANGAVERSE</h1>
            <p class="headpar">The Best Online Manga Store</p>
            <div id="carouselExample" class="carousel slide" data-bs-ride="carousel">
              <div class="carousel-inner">
                <div class="carousel-item active">
                  <img src="https://i.postimg.cc/XvQg3d5y/wallpaperflare-com-wallpaper-6.jpg" alt="img1" loading="lazy">
                </div>
                <div class="carousel-item">
                  <img src="https://i.postimg.cc/TPdrZ826/wallpaperflare-com-wallpaper-9.jpg" alt="img2" loading="lazy">
                </div>
                <div class="carousel-item">
                  <img src="https://i.postimg.cc/Mpw8cMPG/wallpaperflare-com-wallpaper-7.jpg" alt="img3" loading="lazy">
                </div>
              </div>
              <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
              </button>
              <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
              </button>
            <div class="aboutsec">
            <h1 class="text-decoration-underline">About Us</h1>
            <p class="aboutcont">We sell high quality manga at affordable prices. We garuntee customer satisfaction and we
              are always up to <br>date with all the new manga and the classics. We provide worldwide shipping for free with
              no extra costs.
            </p>
          </div>
          <div class="featured">
            <h1 class="text-decoration-underline">Featured Products</h1>
            <div class="products" id="homeprod">
              <div class="container text-center">
                <div class="row">
                    <div class="col-sm-4 d-flex justify-content-center">
                        <div class="card" >
                            <img src="https://i.postimg.cc/1tYFmYHT/jujutsu-kaisen-manga1.jpg" class="card-img-top" alt="product1" loading="lazy">
                            <div class="card-body">
                              <h5 class="card-title">Jujutsu Kaisen Vol.1</h5>
                              <p class="card-text">Volume 1 of Jujutsu Kaisen.</p>
                            </div>
                          </div>
                    </div>
                    <div class="col-sm-4 d-flex justify-content-center">
                        <div class="card" >
                            <img src="https://i.postimg.cc/FKPHyX3W/jujutsu-kaisen-manga2.png" class="card-img-top" alt="product2" loading="lazy">
                            <div class="card-body">
                              <h5 class="card-title">Jujutsu Kaisen Vol.4</h5>
                              <p class="card-text">Volume 4 of Jujutsu Kaisen</p>
                            </div>
                          </div>
                    </div>
                    <div class="col-sm-4 d-flex justify-content-center">
                        <div class="card" >
                            <img src="https://i.postimg.cc/j2mFGbFS/chainsaw-man-vol-1.jpg" class="card-img-top" alt="product3" loading="lazy">
                            <div class="card-body">
                              <h5 class="card-title">Chainsaw Man Vol.1</h5>
                              <p class="card-text">Volume 1 of Chainsaw Man</p>
                            </div>
                          </div>
                    </div>
                  </div>
                <div class="row">
                  <div class="col-sm-4 d-flex justify-content-center">
                    <div class="card">
                        <img src="https://i.postimg.cc/XY661fF6/solo-leveling-vol-1-comic.jpg" class="card-img-top" alt="product4" loading="lazy">
                        <div class="card-body">
                          <h5 class="card-title">Solo Leveling Vol.1</h5>
                          <p class="card-text">Volume 1 of Solo Leveling</p>
                        </div>
                      </div>
                  </div>
                  <div class="col-sm-4 d-flex justify-content-center">
                    <div class="card">
                        <img src="https://i.postimg.cc/jqZZc8xF/bleach-vol-1.jpg" class="card-img-top" id="homeprod" alt="product5" loading="lazy">
                        <div class="card-body">
                          <h5 class="card-title">Bleach Vol.1</h5>
                          <p class="card-text">Volume 1 of Bleach</p>
                        </div>
                      </div>
                  </div>
                  <div class="col-sm-4 d-flex justify-content-center">
                    <div class="card">
                        <img src="https://i.postimg.cc/T1TdpBj0/attack-on-titan-vol-10.jpg" class="card-img-top" alt="product5" loading="lazy">
                        <div class="card-body">
                          <h5 class="card-title">Attack on Titan Vol.10</h5>
                          <p class="card-text">Volume 10 of Attack on Titan</p>
                        </div>
                      </div>
                  </div>
                </div>
    
            </div>
               <router-link to="./"><button id="seemore">See More</button></router-link>
              </div>
            </div>
          </div>
        </div>
      </div>
      </main>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

</style>