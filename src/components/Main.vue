<template>
  <main>
    <!-- inizio sezione1 -->
    <section class="container">
      <!-- testo di sinistra -->
      <div class="row">        
        <div class="col-6">
          <strong>HAC TELLUS, FELIS RISUS AT</strong>
          <p>mattis mattis. Eget euismod semper eget tortor, donec amet, blandit. Tristique facilisi faucibus elementum feugiat in nam in feugiat. Ipsum odio etiam duis facilisis amet vulputate.</p>
          <h1>FOOD IS OUR COMMON</h1>
          <h1>GROUND,A UNIVERSAL</h1>
          <h1>EXPERIENCE</h1>
          <p>Tristique tempus condimentum diam donec. Condimentum<br/> ullamcorper sit elementum hendrerit mi nulla in consequat, ut.<br/> Metus, nullam scelerisque netus viverra dui.</p>
          <img src="@/assets/signature-200x172.jpg" alt="">
        </div>
        <!-- immagine di destra -->
        <div class="col-6 padre">
          <img class="cibo" src="@/assets/info22x.jpg" alt="">
          <span>california rolls - $22</span>
        </div>

      </div>
      <!-- colonne coi sushi   -->
      <div class="container px-4">
        <div class="row gx-5">
          <div class="col">
            <div class="p-3">
              <img class="sushi" src="@/assets/sushi-1.png" alt="">
              <h2>the best table in town</h2>
              <br>
              <hr>
              <br>
              <p>Sed aenean egestas ut aliquam turpis mauris, molestie. Vitae tellus tempor sem id tempus neque, tellus turpis turpis. Morbi tortor id gravida aliquet.</p>
              <button type="button" class="btn btn-outline-secondary">explore the menu</button>
            </div>
          </div>
          <div class="col">
            <div class="p-3">
              <img class="sushi" src="@/assets/sushi-2.png" alt="">
              <h2>perfect for groups</h2>
              <br>
              <hr>
              <br>
              <p>Quam eu proin sit massa condimentum. Volutpat non pulvinar aliquet nunc. Orci elementum in aliquet a gravida vivamus aliquam turpis vitae.</p>
              <button type="button" class="btn btn-outline-secondary">buy avada today</button>
            </div>
          </div>
          <div class="col">
            <div class="p-3">
              <img class="sushi" src="@/assets/sushi-3.png" alt="">
              <h2>Fresh produce everyday</h2>
              <br>
              <hr>
              <br>            
              <p>Hendrerit amet, volutpat leo non, commodo maecenas scelerisque tincidunt. Morbi vulputate morbi purus quisque sit sagittis orci elementum gravida.</p>
              <button type="button" class="btn btn-outline-secondary">learn more about us</button>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- fine sezione1 -->
    <!-- inizio sezione2 -->
    <section class="sector">
       <div class="row">

          <div class="col-6" style="padding: 0px;">
              <img class='back' src="@/assets/slider32x.jpg" alt="">
          </div>

            <div class=" destra col-6 bg-dark text-white">
              <p style="margin-top: 80px;">fine dining experience</p>
              <h1>THE BEST TABLE IN</h1>
              <h1>TOWN</h1>
              <br>
              <p>Pellentesque vitae viverra risus, sagittis.<br/> Venenatis ridiculus scelerisque nisi in urna <br/> nulla.</p>
              <br>
              <button type="button" class="btn btn-outline-light">explore the menu</button>

            </div>

         
       </div>
    </section>
    <!-- fine sezione 2 -->
  </main>
</template>

<script>
export default {

}
</script>

<style>
.padre{
   width: 600px;
  height: 600px;
}
.cibo{
   width: 100%;
   height:100%;
   object-fit: contain;
   transition:transform 0.25s ease;

}
.cibo:hover {
-webkit-transform:scale(1.1); 
transform:scale(1.1);
}

.container{
  margin-top: 80px;
}

.sushi{
  object-position: center;
}
.sector{
  margin-top: 80px;
  
}
.destra{
  text-align: center;
  
}
</style>