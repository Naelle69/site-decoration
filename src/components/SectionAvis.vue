<template>
<div class="avis col">
    <h2> <span>C</span>e <span>Q</span>u'ils <span>D</span>isent <span>D</span>e <span>N</span>ous!</h2>
    <div class="avis1 row justify-content-between">
        <b-card>
            <img class="avatar mb-3" src="@/assets/images/avatar4.svg" rounded="circle" alt="Circle image">
            <b-card-title> Max</b-card-title>
            <b-card-text class="mt-3">
                Lorem ipsum dolor sit amet. dolor sit amet, consectetur adipiscing elit. Nunc, ut auctor lectus aucibus odio. At enim aucacilisis eget.
            </b-card-text>
            <b-card-text class="small text-muted mt-3">Publié il y a 3 jours</b-card-text>
        </b-card>
        <b-card>
            <img class="avatar mb-3" src="@/assets/images/avatar1.svg" rounded="circle" alt="Circle image">
            <b-card-title>Alias007</b-card-title>
            <b-card-text class="mt-3">
                Lorem ipsum dolor sit amet. dolor sit amet, consectetur adipiscing elit. Nunc, ut auctor lectus aucibus odio. At enim aucacilisis eget.
            </b-card-text>
            <b-card-text class="small text-muted mt-3">Publié il y a  1 semaine</b-card-text>
        </b-card>
        <b-card>
            <img class="avatar mb-3" src="@/assets/images/avatar2.svg" rounded="circle" alt="Circle image">
            <b-card-title>Lydia</b-card-title>
            <b-card-text class="mt-3">
                Lorem ipsum dolor sit amet. dolor sit amet, consectetur adipiscing elit. Nunc, ut auctor lectus aucibus odio. At enim aucacilisis eget.
            </b-card-text>
            <b-card-text class="small text-muted mt-3">Publié il y a 3 jours</b-card-text>
        </b-card>
        <b-card>
            <img class="avatar mb-3" src="@/assets/images/avatar3.svg" rounded="circle" alt="Circle image">
            <b-card-title>Mario89</b-card-title>
            <b-card-text class="mt-3 ">
                Lorem ipsum dolor sit amet. dolor sit amet, consectetur adipiscing elit. Nunc, ut auctor lectus aucibus odio. At enim aucacilisis eget.
            </b-card-text>
            <b-card-text class="small text-muted mt-3">Publié il y a 4 jours</b-card-text>
        </b-card>
    </div>
</div>
</template>


<style scoped>
span{
    color:#D79D66;
}

h2{
    color: white;
    padding-top: 50px;
}

.avis{
    background-color: #001E00;
    padding-left: 100px;
}
.avis1{
    width: 100%;
    height: auto;
    padding-top: 100px;
    padding-left: 150px;
    padding-right: 150px;
    padding-bottom: 100px;
    margin: 0%;
}

b-card{
    width: 23%;
    height: auto;
    box-shadow: #000000 1px 1px 20px 1px;
    color: white;
    padding: 30px;
    display: flex;
    flex-direction: column;
    align-items: center;
}

.avatar{
    height: 60px;
    width: 60px;
}
</style>