<template>
    <div class="interieur">   
        <div class="col titre">
            <div class="col"><h2> <span>E</span>quipez et <span>D</span>esignez vos <span>I</span>ntérieurs</h2></div>
            <div class="col"><p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
                Nunc, ut auctor lectus . At enim aucacilisis eget. Condimenpellentesque 
                risus, tincidunt. Pro morbi tempor, curabitur neque quam convallis. 
                Nunc, ut auctor lectus . At enim aucacilisis eget. Condimenpellentesque risus, 
                tincidunt. Pro morbi tempor, curabitur neque quam convallis.</p></div>
            <div class="col"><b-button class="button1" href="#">En savoir plus</b-button></div>
        </div>
        <div class="col col-cols-4">
            <div class="grid row">
                <div class="col card1">
                    <b-card title="Card Title"  fluid alt="Responsive image"
                        img-top tag="article" style="max-width: 20rem;" class="mb-2">
                        <img src="@/assets/images/image2.jpg" class="img-fluid" alt="Salon">
                        <div class="texte1">
                            <h3> Rangements </h3>
                            <b-card-text>     
                                Lorem ipsum dolor sit amet. At enim aucacilisis eget. Condimenpellentesque rhoncus risus, tincidunt. Pro morbi tempor, curabitur neque quam convallis.
                            </b-card-text>
                            <b-button class="button2 img-fluid" href="#" variant="primary">Découvrir</b-button>   
                        </div>
                    </b-card>   
                </div>
                <div class="col card1">
                    <b-card title="Card Title"  fluid alt="Responsive image"
                        img-top tag="article" style="max-width: 20rem;" class="mb-2">
                        <img src="@/assets/images/image2.jpg" class="img-fluid" alt="Salon">
                        <div class="texte1">
                            <h3> Salon </h3>
                            <b-card-text>     
                                Lorem ipsum dolor sit amet, ut auctor lectus aucibus consectetur adipiscing elit. dolor sit a Pro morbi tempor, curabitur neque quam convallis.
                            </b-card-text>
                            <b-button class="button2 img-fluid" href="#" variant="primary">Découvrir</b-button>   
                        </div>
                    </b-card>   
                </div>
                <div class="col card1">
                    <b-card title="Card Title"  fluid alt="Responsive image"
                        img-top tag="article" style="max-width: 20rem;" class="mb-2">
                        <img src="@/assets/images/img-hp.jpeg" class="img-fluid" alt="Salon">
                        <div class="texte1">
                            <h3> Cuisine </h3>
                            <b-card-text>     
                                Lorem ipsum dolor sit amet, consectetur  elit. Nunc,us odio. At enim aucacilisis eget. Condimenpellentesque rhoncus risus, tincidunt. Pro morbi tempor, onvallis.
                            </b-card-text>
                            <b-button class="button2 img-fluid" href="#" variant="primary">Découvrir</b-button>   
                        </div>
                    </b-card>   
                </div>
                <div class="col card1">
                    <b-card title="Card Title"  fluid alt="Responsive image"
                        img-top tag="article" style="max-width: 20rem;" class="mb-2">
                        <img src="@/assets/images/img-hp.jpeg" class="img-fluid" alt="Salon">
                        <div class="texte1">   
                            <h3> Chambre </h3>
                            <b-card-text>     
                                Lorem ipsum dolor sit amet, At enim aucacilisis eget. Condimenpellentesque rhoncus risus, tincidunt. Pro morbi tempor, curabitur neque quam convallis.
                            </b-card-text>
                            <b-button class="button2 img-fluid" href="#" variant="primary">Découvrir</b-button>   
                        </div>
                    </b-card>   
                </div>
            </div>
        </div>
    </div>
</template>



<style scoped>
@media screen and (min-width:1021px){
.texte1{
    margin: 40px;
    height: 40%; 
}

span{
    color:#D79D66;
}
.col-cols-4{
margin-left: 150px;
margin-right: 150px;
align-self:center;
}
.grid{
width: 100%;
display: flex;
justify-items: space-between;
grid-gap: 25px;
display: grid;
grid-template-columns: 25% 25% 25% 25%;
}

.interieur{
width: 100%;
background-color: rgb(0, 30, 0);
padding: 100px;
margin: 0%;
}

.card1{
width: 300px;
height: 700px;
background-color: #001E00;
border: #ffffff solid 1px;
padding: 0%;
transition: ease-in-out 0.3s;
color: #ffffff;
}

.card1:hover{
background-color: #ffffff;
color:#001E00;
font-weight: bolder;
transform: scale(1.1);
cursor: pointer; 
box-shadow: #fbe5d0 1px 1px 25px 1px;
}

img{
    height: 350px;
    width: 100%;
    border-radius: 0px 0px 160px 160px;
}

.titre{
    margin-bottom: 100px;
    width: 60%;
    color: #ffffff;
}

b-card-text{
display: flex;
text-align: justify;
justify-content: flex-start;
padding-top: 20px;
padding-bottom: 20px;
}

.button1{
    background-color:#D79D66 ;
    color: white;
    padding: 5px 15px 8px 15px;
    border-radius: 15px;
}

.button2{
    background-color:rgb(215, 157, 102) ;
    color: white;
    padding: 5px 15px 8px 15px;
    border-radius: 15px;
}

h3{
    font-size: 24px;
}
}
</style>