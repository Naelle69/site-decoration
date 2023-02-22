<template>
<div class="row row-cols-2">
    <div class="col titre">
        <div class="col mb-3"><h2>Déjà <span>10ans</span> que nous vous proposons des produits de qualité et au design soigné</h2></div>
        <div class="col mb-3"><p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc, ut auctor lectus . At enim aucacilisis eget. Condimenpellentesque risus, tincidunt. Pro morbi tempor, curabitur neque quam convallis. Nunc, ut auctor lectus . At enim aucacilisis eget. Condimenpellentesque risus, tincidunt. Pro morbi tempor, curabitur neque quam convallis.</p></div>
        <b-link class="link" href="#foo"><span>Célébrons ensemble nos 10 ans !</span></b-link>
    </div>
  

    <div class="grid">
        <div class="col1"> 
            <img src="@/assets/images/image1-section2.jpg" class="img-fluid row1" alt="Salon" />
            <img src="@/assets/images/image3.jpeg" class="img-fluid row2" alt="Salon" />
        </div>
        <div class="col2">
            <img src="@/assets/images/image-hp.jpg" class="img-fluid row4" alt="Salon" />
            <img src="@/assets/images/chambre.jpg" class="img-fluid row3" alt="Salon" />   
        </div>
        <img src="@/assets/images/image2-section2.png" class="img-fluid col3" alt="Salon" />    
    </div>
</div>

</template>


<style scoped>

/* a.disabled {
  pointer-events: none;
} */
span{
    color:#D79D66;
}

.link{
  text-decoration:underline;
  color:#D79D66;
}
.grid {
    display: grid;
    grid-template-columns: 33% 33% 33%;
    grid-gap: 10px;
  }
  .col1 {
    grid-column: 1 / 2;
    height: 100%;
    grid-gap: 10px;
  }
  .row1 {
    height: 30%;
    width: 100%;
  }
  .row2 {
    height: 68%;
    width: 100%;
    margin-top: 10px;
  }

  .row3 {
    height: 30%;
    width: 100%;
  }
  .row4 {
    height: 68%;
    width: 100%;
    margin-bottom: 10px;
  }
  .col2 {
    grid-column: 2 / 3;
    height: 100%;
    grid-gap: 10px;
  }
  .col3 {
    grid-column: 3 / 4;
    height: 100%;
    width: 100%;
  }
  .row-cols-2{
   background-color: #001E00;
   padding: 100px;
   margin: 0%;
   display: flex;
   align-items: center;
  transform: translateY(-112px);
  }

  .titre{
    padding-right: 150px;
    color: white;
  }
</style>