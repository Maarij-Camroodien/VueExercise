<template>
    <div>
  <nav class="navbar navbar-expand-lg">
          <div class="container-fluid">
            <a class="navbar-brand" href="../index.html">MANGAVERSE</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
              <span><i class="bi bi-list"></i></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
              <div class="navbar-nav ms-auto">
                  <router-link id="links" to="/">HOME</router-link>
                  <router-link id="links" to="/products">PRODUCTS</router-link>
                  <router-link id="links" to="/admin">ADMIN</router-link>
                  <router-link id="links" to="/checkout">CHECKOUT</router-link>
              </div>
            </div>
          </div>
        </nav>
      </div>
  </template>
  
  <script>
      export default {
          
      }
  </script>
  
  <style scoped>
  
  </style>