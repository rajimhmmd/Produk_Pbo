<template>
    <nav class="navbar navbar-expand-lg navbar-light bg-primary">
  <a class="navbar-brand" href="#" style="color: #F8F8FF;"> <b>Good_Style</b> </a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
    <div class="navbar-nav">
      <ul class="navbar-nav ms-auto">
                                <li class="nav-item active">
                                    <NuxtLink to="/" class="text-white cd-md-3">
                                        Home
                                    </NuxtLink>
                                </li>
                                <li class="nav-item active">
                                    <NuxtLink to="/product" class="text-white col-md-3">
                                        Product
                                    </NuxtLink>
                                </li>
                                <li class="nav-item active">
                                    <NuxtLink to="/contact" class="text-white col-md-3">
                                        Contact
                                    </NuxtLink>
                                </li>
                                <li class="nav-item active">
                                    <NuxtLink to="/map" class="text-white col-md-3">
                                        Map
                                    </NuxtLink>
                                </li>
                            </ul>
    </div>
  </div>
</nav>
</template>