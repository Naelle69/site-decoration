<template>
<nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
    <img src="@/assets/images/logobeige.svg" href="#" width="20">
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarScroll" aria-controls="navbarScroll" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarScroll">
      <ul class="navbar-nav me-auto my-2 my-lg-0 navbar-nav-scroll" style="--bs-scroll-height: 100px;">
        <li class="nav-item">
          <a class="nav-link" aria-current="page" href="#">Acceuil</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Produits
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Cuisine</a></li>
            <li><a class="dropdown-item" href="#">Meubles salon</a></li>
            <li><a class="dropdown-item" href="#">Meubles salle à manger</a></li>
            <li><a class="dropdown-item" href="#">Meubles d'extérieur</a></li>
            <li><a class="dropdown-item" href="#">Dressing</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Promotions</a></li>
          </ul>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Pièces
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Salon</a></li>
            <li><a class="dropdown-item" href="#">Cuisine</a></li>
            <li><a class="dropdown-item" href="#">Chambre</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Inspiration</a></li>
          </ul>
        </li>
        <li class="nav-item">
          <a class="nav-link">Blog déco</a>
        </li>
      </ul>
      <form class="d-flex" role="search">
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success" type="submit">Rechercher</button>
      </form>
    </div>
  </div>
</nav>
</template>



<style scoped>
nav{
    background-color: #001E00;
    border-radius: 40px;
    color:white;
    height: 80px;
    margin-right: 100px;
    margin-left: 100px;
    margin-top: 30px;
    padding-left: 50px;
    padding-right: 50px;
    z-index: 5;
}

.collapse{
  margin-left:500px;
  display: flex;
  justify-content: space-evenly;
}

a{
    color: rgb(255, 255, 255);
}

a:hover{
color: #D79D66;
}
.dropdown-item{
  color: #001E00;
}
</style>