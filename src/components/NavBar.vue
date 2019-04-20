<template>

  <nav class="navbar navbar-expand-lg navbar-light fixed-top">
    <a class="navbar-brand" href="#">RAVEN PROJECT</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <i class="fas fa-bars"></i>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav ml-auto topnav">
        <li class="nav-item">
          <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Our Projects</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Stats</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            RavenDOI
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdown">
            <a class="dropdown-item" href="#">1</a>
            <a class="dropdown-item" href="#">2</a>
            <a class="dropdown-item" href="#">3</a>
          </div>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contact</a>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
</script>

<style lang="scss" scoped>

nav {
  padding: 25px;
  transition: all 1.2s;
  background-color: rgba(248, 248, 248, 0);
  border-color: rgba(231, 231, 231, 0);
  background-color: rgba(0,0,0,0.8) !important;
}

.navbar-light .navbar-nav .nav-link:hover {
  color: #cd65b5;
}

/* Navbar elements */
.navbar-nav > li > a {
  text-transform: uppercase;
  color: rgba(255,255,255,0.8);
  font-size: 14px;
  font-weight: 400;
  letter-spacing: 1px;
}

.navbar-brand {
  font-size: 24px;
  color: rgba(255,255,255,0.8);
  font-weight: 600;
  text-transform: uppercase;
}

.navbar-toggler {
  border-radius: 0;
}

.navbar-toggler:hover {
  background-color: #C54DAA;
  border-color: #C54DAA;
}

.navbar-toggler:hover > .fas.fa-bars {
  color:white;
}


/*

.on {
  padding: 0 !important;
}
.navbar-default .navbar-nav > .active > a, .navbar-default .navbar-nav > .active > a:hover, .navbar-default .navbar-nav > .active > a:focus {
  color: #C54DAA !important;
  background-color: transparent;
}

.section-title {
  margin-bottom: 50px;
}
.section-title p {
  font-size: 18px;
  color: #888;
}*/
</style>
