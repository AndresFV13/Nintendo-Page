<template>
  <div class="d-flex justify-content-between container-navigation">
    <div class="d-flex">
      <a href="#" class="me-3">
        <img width="120" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0d/Nintendo.svg/1024px-Nintendo.svg.png" alt="nintendo">
      </a>
      <form action="" class="d-flex">
        <div class="d-flex align-items-center p-1 me-3">
          <i class="bi bi-search"></i>
          <input class="search ms-1" type="search">
        </div>
        <li class="nav-item dropdown d-flex align-items-center">
          <a class="nav-link dropdown-toggle text-danger fw-semibold" data-bs-toggle="dropdown" href="#" role="button" aria-expanded="false">Todas las cat...</a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Todas las categorias</a></li>
            <li><a class="dropdown-item" href="#">juegos</a></li>
            <li><a class="dropdown-item" href="#">Noticias y eventos</a></li>
            <li><a class="dropdown-item" href="#">Soporte</a></li>
          </ul>
        </li>
      </form>
    </div>
    <div class="d-flex align-items-center">
      <div class="me-3">
        <i class="bi bi-gear-fill"></i>
        <a class="link-offset-2 link-underline link-underline-opacity-0 fw-semibold" href=""> Soporte </a>
      </div>
      <div class="me-3">
        <i class="bi bi-heart-fill"></i>
        <a class="link-offset-2 link-underline link-underline-opacity-0 fw-semibold" href=""> Lista de deseos </a>
      </div>
      <div class="me-3">
        <i class="bi bi-person-fill"></i>
        <a class="link-offset-2 link-underline link-underline-opacity-0 fw-semibold" href=""> Iniciar sesión / Regístrate </a>
      </div>
    </div>
  </div>
  <div class="d-flex align-items-center justify-content-center p-2">
      <div class="me-3 ms-3">
        <i class="bi bi-joystick"></i>
        <a class="link-offset-2 link-underline link-underline-opacity-0 fw-semibold" href=""> Juegos </a>
      </div>
      <div class="me-3 ms-3">
        <i class="bi bi-nintendo-switch"></i>
        <a class="link-offset-2 link-underline link-underline-opacity-0 fw-semibold" href=""> Nintendo Switch </a>
      </div>
      <div class="me-3 ms-3">
        <i class="bi bi-chat-right-text-fill"></i>
        <a class="link-offset-2 link-underline link-underline-opacity-0 fw-semibold" href=""> Noticias y eventos </a>
      </div>
    </div>
</template>
<script>

export default {

    setup(){
   
    }
}
</script>
<style scoped>
  .container-navigation{
    border-bottom: 1px solid #DADADA;
  }
  
  .bi-search{
    color: #E7000A;
  }

  .bi-gear-fill .bi-heart-fill .bi-person-fill{
    background-color: #484848;
  }

  .link-offset-2{
    color: #484848;
  }

</style>