<template>
    <section class="container-fluid sezione1">
          <header class="row absolute">
              <!-- immagine -->
              <div class="sinistra col-6">
                  <img class="logo" src="@/assets/logo-restaurant.png" alt="">
              </div>
              <!-- navbar -->
            <div class="destra col-6">
                  <nav class="navbar navbar-expand-lg navbar-light text-secondary  float-end">
                <div class="container-fluid">
                    <a class="navbar-brand text-white" href="#">Home</a>
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
                  <!-- fine navbar -->
            </div>   
            </header>
<div class="row">
    <div class="sinistra col-6 text-white">
                <div class="linea"></div>
              <p style="margin-top: 300px; margin-right:200px;">the best table in town</p>
              <h1 class="fusion">FINE DINING<br>EXPERIENCE</h1>
              <br>
              <p class="font">Pellentesque vitae viverra risus, sagittis.<br/> Venenatis ridiculus scelerisque nisi in urna <br/> nulla. Sit tempor a et nisl, ac felis.</p>
              <br>
              <button type="button" class="btn btn-outline-light">buy avada today</button>

          </div>

          <div class="destra col-6" style="padding: 0px;">
              <img class='back' src="@/assets/slider52x.jpg" alt="">
          </div>
</div>
          

    </section>
</template>

<script>
export default {

}
</script>

<style lang="scss">
.linea{
    border: 1px solid;
    color: white;
}
.nav-item a{
    color: gray !important;
}
.fusion{
    
   font-weight: 700;
   font-size: 60px;

    
}
.sezione1{
    position: relative;
    
}
.absolute{
    position: absolute;
    width: 100%;
    left: 0px;
    
    
}
.back{
    width:100%; 
    min-width:600px; 
    margin:auto;
    

}
.destra{
    padding: 0px;
    
}
.sinistra{
    text-align: center;
    background-color: #030303;
    
}
.logo{
    margin-top: 50px;
    margin-right: 300px;
}

   

</style>