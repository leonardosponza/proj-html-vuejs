<template>
    <section class="sezione1">
          <header>
              <div class="sinistra">
                  <img class="logo" src="@/assets/logo-restaurant.png" alt="">
              </div>
            <div class="destra">
                  <nav class="navbar navbar-expand-lg navbar-light float-end">
                <div class="container-fluid">
                    <a class="navbar-brand" href="#">Home</a>
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                    </button>
                    <div class="collapse navbar-collapse" id="navbarNavDropdown">
                    <ul class="navbar-nav">
                        <li class="nav-item">
                        <a class="nav-link" href="#">history</a>
                        </li>
                        <li class="nav-item">
                        <a class="nav-link" href="#">team</a>
                        </li>
                        <li class="nav-item">
                        <a class="nav-link" href="#">menu</a>
                        </li>
                        <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            takeout
                        </a>
                        <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                            <li><a class="dropdown-item" href="#">simple product</a></li>
                            <li><a class="dropdown-item" href="#">variable product</a></li>    
                        </ul>
                        </li>
                        <li class="nav-item">
                        <a class="nav-link" href="#">bulletin</a>
                        </li>
                        <li class="nav-item">
                        <a class="nav-link" href="#">reservation</a>
                        </li>
                    </ul>
                      </div>
                   </div>
                  </nav>
            </div>   
            </header>

          <div class="sinistra bg-dark text-white">
              <p>the best table in town</p>
              <h1>FINE DINING</h1>
              <h1>EXPERIENCE</h1>
              <p>Pellentesque vitae viverra risus, sagittis. Venenatis ridiculus scelerisque nisi in urna nulla. Sit tempor a et nisl, ac felis.</p>
              <button type="button" class="btn btn-outline-secondary text-white">buy avada today</button>

          </div>

          <div class="destra">
              <img class='back' src="@/assets/slider52x.jpg" alt="">
          </div>

    </section>
</template>

<script>
export default {

}
</script>

<style lang="scss">
header{
    margin-top: 40px;
    margin-left: 100px;
    
}
.sezione1{
    position: relative;
}
.back{
    width:100%; 
    min-width:600px; 
    margin:auto;
}
</style>