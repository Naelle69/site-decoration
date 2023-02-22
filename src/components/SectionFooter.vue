<template>
    <!-- Footer -->
<footer class="text-center text-white justify-content-center" style="background-color: rgba(0, 30, 0);">
  <!-- Grid container -->
  <div class="containerfooter mb-6">
    <!-- Section: Form -->
    <section class="newsletter">
      <form action="">
        <!--Grid row-->
        <div class="inscription">
          <!--Grid column-->
          <div class="col-auto">
            <h3 style="color: rgb(215, 157, 102);"> Newsletter </h3>
            <p class="pt-2">
              <strong>Inscrivez-vous à notre newsletter pour ne rien rater de nos bons plans</strong>
            </p>
          </div>
          <!--Grid column-->
          <div class="bouton3 row">
            <!--Grid column-->
            <div class="col-auto">
              <!-- Submit button -->
              <button type="submit" class="btn btn-outline-light mb-4" style="background-color: rgb(215, 157, 102);">Inscription</button>
            </div>
            <!--Grid column-->

            <!--Grid column-->
            <div class="col-md-5 col-12">
              <!-- Email input -->
              <div class="form-outline form-white mb-4"> 
                <input type="email" id="form5Example21" class="form-control" />
              </div>
            </div>
            <!--Grid column-->
          </div>

          
        </div>
        <!--Grid row-->
      </form>
    </section>
    <!-- Section: Form -->

   

    <!-- Section: Links -->
    <section class="liens row">
      <!--Grid row-->
        <div class="col-lg-3 col-md- mb-4 mb-md-0">
          <h5 class="text-uppercase" style="color: rgb(215, 157, 102);">L'entreprise</h5>

          <ul class="list-unstyled mb-0">
            <li>
              <a href="#!" class="text-white">Concept</a>
            </li>
            <li>
              <a href="#!" class="text-white">Plan du site</a>
            </li>
            <li>
              <a href="#!" class="text-white">FAQS</a>
            </li>
          </ul>
        </div>
        <!--Grid column-->

        <!--Grid column-->
        <div class="col-lg-3 contacts col-md-6 mb-4 mb-md-0">
          <h5 class="text-uppercase" style="color: rgb(215, 157, 102);">Contacts</h5>

          <ul class="list-unstyled mb-0">
            <li>
              <a href="#!" class="text-white">Tél: 04 22 33 52 54</a>
            </li>
            <li>
              <a href="#!" class="text-white">Mail: contact@luxuryhouse.fr</a>
            </li>
            <li>
              <a href="#!" class="text-white">Adresse: 2 rue Marc, 94000 Créteil</a>
            </li>
                    <!-- Section: Social media -->
            <section class="mt-2">
              <!-- Facebook -->
              <a class="btn m-1" href="#!" role="button">
                <img src="@/assets/images/facebook.svg" class="img-fluid" alt="Luxury House">
              </a>

              <!-- Instagram -->
              <a class="btn m-1" href="#!" role="button">
                <img src="@/assets/images/instagram.svg" class="img-fluid" alt="Luxury House">
              </a>

              <!-- Youtube -->
              <a class="btn m-1" href="#!" role="button">
                <img src="@/assets/images/youtube.svg" class="img-fluid" alt="Luxury House">
              </a>

              <!-- pinterest -->
              <a class="btn m-1" href="#!" role="button">
                <img src="@/assets/images/pinterest.svg" class="img-fluid" alt="Luxury House">
              </a>
            </section>
            <!-- Section: Social media -->
          </ul>
        </div>
        <!--Grid column-->

        <!--Grid column-->
        <div class="col-lg-3 col-md-6 mb-4 mb-md-0">
          <h5 class="text-uppercase" style="color: rgb(215, 157, 102);">Mentions légales</h5>

          <ul class="list-unstyled mb-0">
            <li>
              <a href="#!" class="text-white">Conditions générales</a>
            </li>
            <li>
              <a href="#!" class="text-white">Politiques de confidentialité</a>
            </li>
            <li>
              <a href="#!" class="text-white">Cookies</a>
            </li>  
          </ul>
        </div>
        <!--Grid column-->
      <!--Grid row-->
    </section>
    <!-- Section: Links -->
  </div>
  <!-- Grid container -->

  <!-- Copyright -->
  <div class="mt-4 p-4" style="background-color: rgba(0, 30, 0); color: rgb(215, 157, 102);">
    © 2023 Copyright /
    <a class="text-decoration-none" style="color: rgb(215, 157, 102);">Site édité par IBINGA Naëlle</a>
  </div>
  <!-- Copyright -->
</footer>
<!-- Footer -->
</template>


<style scoped>
@media screen and (min-width:1021px){
.containerfooter{
  display: flex;
  flex-direction: row;
  padding: 100px;
  margin: 0%;
  margin-left: 100px;
  margin-right: 100px;
  display: flex;
  justify-content: space-between;
  box-shadow: #000000 1px 1px 20px 1px;
  width: 90%;
  height: auto;
  gap:50px;
}

.newsletter{
  padding: 50px;
  display: flex;
  justify-content: center;
  width: 35%;
  height: 300px;
  box-shadow: #000000 1px 1px 20px 1px;
}

.liens{
  width: 65%;
  height: 300px;
  margin: 0px  0px  0px  0px;
  padding-top: 70px;
  display: flex;
  justify-content: center;
  align-items: flex-start;
  text-decoration: none;
  border-bottom: 1px solid #D79D66;
  border-top: 1px solid #D79D66;
}

.contacts{
  width: 40%;
}

.col-lg-3{
  width: 30%;
}

a{
  text-decoration: none;
}
}
</style>