<template>
  <div>
      <!-- <nav class="navbar navbar-expand-lg bg-body-tertiary">
          <div class="container-fluid">
            <router-link to="/"><img src="" alt="LOGO" loading="lazy" class="logo"></router-link>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
              <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
                <li class="nav-item">
                  <router-link to="/" class="nav-link">Home</router-link>
                </li>
                <li class="nav-item">
                  <router-link to="/about" class="nav-link">About</router-link>
                </li>
                <li class="nav-item">
                  <router-link to="/resume" class="nav-link">Resume</router-link>
                </li>
                <li class="nav-item">
                  <router-link to="/testimonial" class="nav-link">Testimonial</router-link>
                 </li>
                 <li class="nav-item">
                  <router-link to="/projects" class="nav-link">Projects</router-link>
                  </li>
                  <li class="nav-item">
                   <router-link to="/contact" class="nav-link">Contact Us</router-link>
                   </li>
              </ul>
            </div>
          </div>
        </nav> -->
        <nav class="navbar navbar-expand-lg bg-body-tertiary">
          <div class="container-fluid">
            <router-link to="/"><img src="" alt="LOGO" loading="lazy" class="logo" ></router-link>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
              <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                <li class="nav-item">
                  <router-link to="/" class="nav-link">Home</router-link>
                </li>
                <li class="nav-item">
                  <router-link to="/about" class="nav-link">About</router-link>
                </li>
                <li class="nav-item dropdown">
                  <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                    Products
                  </a>
                  <ul class="dropdown-menu">
                    <li class="nav-item">
                      <router-link to="/products" class="nav-link">Womens Clothing</router-link>
                      </li>
                      <li class="nav-item">
                        <router-link to="/products" class="nav-link">Mens Clothing</router-link>
                        </li>
                        <li class="nav-item">
                          <router-link to="/products" class="nav-link">Kids Clothing</router-link>
                          </li>
                          <li class="nav-item">
                            <router-link to="/products" class="dropdown-item  nav-link" >Products</router-link>
                            </li>
                  </ul>
                </li>
                <li class="nav-item">
                  <router-link to="/help" class="nav-link">Help Page</router-link>
                  </li>
                  <li class="nav-item">
                   <router-link to="/contact" class="nav-link">Contact Us</router-link>
                   </li>
              </ul>
              <form class="d-flex" role="search">
                <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                <button class="btn btn-outline-success" type="submit">Search</button>
              </form>
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
ul li a{
 margin: 5px; 
}
</style>

