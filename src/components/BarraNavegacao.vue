<!-- HTML -->

<template>
  <nav class="navbar navbar-expand">
    <div class="container-fluid">
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <RouterLink class="nav-link" to="/">Primeira geração</RouterLink>
          </li>

          <li class="nav-item">
            <RouterLink class="nav-link" to="/geracao2">Segunda geração</RouterLink>
          </li>

          <li class="nav-item">
            <RouterLink class="nav-link" to="/geracao3">Terceira geração</RouterLink>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>


<style scoped>


  .navbar{

    padding: 0;
    
  }

  .container-fluid{

    height: 70px;
    background-color: #8f8f8f;

  }

  .navbar-nav{

    margin: 0 auto;

  }

  .nav-link{
    font-size: 1.05rem;
  }

</style>