<template>
 <main>
    <h1 class="text-decoration-underline text-center">MANGAVERSE</h1>
    <div class="dropdown">
      <button class="btn btn-secondary dropdown-toggle" type="button" data-bs-toggle="dropdown" aria-expanded="false">
        Filter Products
      </button>
      <div class="dropdown-menu">
        <div class="pricesortbtn">
          <button class="btn" id="pricesortbtn">Sort by Price</button>
          </div>
          <div class="namesortbtn">
            <button class="btn" id="namesortbtn">Sort by Name</button>
          </div>
        </div>
    </div>
    <div class="productPage">
      <div class="row productsdisp">
      </div>
    </div>
    <div>
    <div class="container">
        <div class="row">
            <div id="productcard" class="col" v-for="item in data" :key="item.ID">
                <div class="card" style="width: 18rem;">
                <img :src="item.image" class="card-img-top" :alt="item.name">
                 <div class="card-body">
                    <h4>{{ item.name}}</h4>
                    <p>{{ item.detail }}</p>
                    <p>{{ item.price }}</p>
                </div>
                </div>
            </div>
        </div>
    </div>
</div>
  </main>   
</template>


<script>
export default {
    data(){
        return {
            data:[]
        }
    },
    methods: {
async fetchData() {
const res = await fetch('https://maarij-camroodien.github.io/jsonSeverVue/products.json')
let parsedData = await res.json()
this.data = parsedData.manga;
}
    },
    mounted() {
        this.fetchData()
    }
}
</script>

<style scoped>

</style>