<template>
<nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
      <nuxt-link to="/" class="navbar-brand">1位~5位</nuxt-link>
     
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNav"
      >
    
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <nuxt-link  class="nav-link" to="/index2">6位~10位</nuxt-link>
          </li>
          <li class="nav-item">
          <nuxt-link  class="nav-link" to="/index3">11位~15位</nuxt-link>
          </li>
          
        </ul>
      </div>
    </div>
  </nav>
</template>