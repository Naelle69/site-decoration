<template>

<div class="club">
  <div class="cardwhite row">
    <b-card class="cardtext">
      <b-card no-body class="overflow-hidden" style="max-width: 740px;">
        <b-card-body title="Horizontal Card">
          <b-card-text>
            <div class="col mb-4"><h2> LUXURY Familly : le club qui apporte satisfaction à tout vos besoins !</h2></div>
            <div class="col"><p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc, ut auctor lectus . 
              At enim aucacilisis eget. Condimenpellentesque risus, tincidunt. </p>
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc, ut auctor lectus . 
              At enim aucacilisis eget.</p>
            </div>
            <b-button class="button1" href="#">Devenir membre</b-button>
          </b-card-text>
        </b-card-body>
      </b-card>
    </b-card> 
    <img src="@/assets/images/club.jpg" class="img-club" alt="Luxury House">
  </div>
  
</div>


</template>


<style scoped>
@media screen and (min-width:1021px){
.club{
background-color: #001E00;
height: 700px;
width: 100%;
margin: 0%;
padding: 0%;
display: flex;
align-items: center;
justify-content: end;

}

.cardwhite{
background-color: #ffffff;
border-radius: 100px 0px 0px 100px;
border: #000000 solid 5px;
box-shadow: #000000 2px 2px 40px 2px;
width: 70%;
height: 600px;
padding-left: 40px;
display: flex;
align-items: center;
justify-content: center;
flex-direction: row;
}

.cardwhite:hover{
box-shadow: #fbe5d0 2px 2px 40px 2px;
border:none;
}

.cardtext{
box-shadow: #f6d4b5 1px 1px 20px 1px;
background-color: #ffffff;
width: 50%;
height: 87%;
border-radius:70px;
display: flex;
align-items: center;
padding-left: 60px;
padding-right: 60px;
text-align: justify;
color: #001E00;
z-index: 1;
}

.img-club{
  width: 50%;
  height: 50%;
  transform: translateX(-20px);
}

.col p{
  font-size: 16px;
}

.button1{
    background-color:#D79D66 ;
    color: white;
    padding: 5px 15px 8px 15px;
    border-radius: 15px;
}

}
</style>



