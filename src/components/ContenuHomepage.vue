<template>
        <div class="container2 col-cols-2">
            <div class="titre"><h1>LUXURY HOUSE</h1></div>
            <div class="col texte1">
                <div class="col"><h2><span>D</span>onnez <span>V</span>ie à vos <span>I</span>ntérieurs</h2></div>
                <div class="col pb-4"><p>Lorem ipsum <span>dolor sit</span> amet, consectetur adipiscing elit. Nunc, ut auctor lectus . At enim aucacilisis eget. Condimenpellentesque risus, tincidunt. Pro morbi tempor, neque quam <span>convallis</span>.</p></div>
                <div class="col"><b-button class="button1" href="#">En savoir plus</b-button></div>
                <div class="col card1">
                    <b-card class="" title="Card Title"  fluid alt="Responsive image"
                        img-top tag="article" style="max-width: 20rem;">
                        <img src="@/assets/images/img-hp.jpeg" class="img-fluid" alt="Salon" height="300">
                        <div class="texte">
                            <h3 class="pb-4"> Projets récents </h3>
                            <b-card-text class="pb-4">     
                                Lorem ipsum dolor sit amet, ut auctor lectus aucibus consectetur adipiscing elit. dolor sit amet, consectetur adipiscing elit. Nunc, ut auctor lectus aucibus odio. At enim aucacilisis eget. Condimenpellentesque rhoncus risus, tincidunt.
                            </b-card-text>
                            <b-button class="button2 img-fluid" href="#" variant="primary">Découvrir</b-button> 
                        </div>  
                    </b-card>   
                </div>
            </div>
        </div>
</template>


<style scoped>
@media screen and (min-width:1021px){
h1{
    color: white;
    font-size: 96px;
    font-weight: lighter;
    margin-bottom: 60px;
}

h2{
    color: #001E00;
    font-size: 56px;
    font-weight:normal;
    padding-top: 40px;
}

p{
    color: #001E00;
    font-size: 26px;
    font-weight:normal;
}

span{
    color:#D79D66;
}

h3{
    color:white;
}

.container2{
width: 100%;
height: 970px; 
padding: 0%;
margin: 0%; 
background-image: url(../assets/images/image-f-hp.jpg);
background-repeat: no-repeat;
background-size: 100%;
/* position: relative;
top:-90px */
transform: translateY(-112px);
}

.card1{
width: 350px;
height: 967px;
position: relative;
top: -777px;
left: 1200px;
background-color: #001E00;
padding: 0%;
}

img{
width: 100%;
height: 60%;
border-radius: 0px 0px 160px 160px;
}

.titre{
height: 50%;
width: 100%;
padding-left: 110px;
display: flex;
align-items: flex-end;
background-color: #001e00b0;
}

.texte1{
height: 50%;
width: 100%;
padding-left: 110px;
padding-right: 50%;
background-color: #ffffffc7;
}

.texte{
    margin: 40px;
    height: 40%; 
}

b-card-text{
color: white;
display: flex;
text-align: justify;
justify-content: flex-start;
}

.button1{
    background-color:#D79D66 ;
    color: white;
    padding: 5px 15px 8px 15px;
    border-radius: 15px;
}

.button2{
    background-color:#D79D66 ;
    color: white;
    padding: 5px 15px 8px 15px;
    border-radius: 15px;
}
}
</style>