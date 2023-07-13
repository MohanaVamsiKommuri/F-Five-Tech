<template>
  <div class="about">
    <div class="block header-div">
      <nav class="navbar navbar-expand-sm text-white col-xl-12 col-md-12 col-sm-12 navbar-head shadow-lg p-4">
        <div class="container-fluid">
          <button class="navbar-toggler text-white bg-white" type="button" data-bs-toggle="collapse"
            data-bs-target="#navbarTogglerDemo03" aria-controls="navbarTogglerDemo03" aria-expanded="false"
            aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <!-- navbar starts here -->
          <div class="collapse navbar-collapse" id="navbarTogglerDemo03">
            <ul class="navbar-nav ms-auto">
              <li class="nav-item">
                <router-link class="nav-link text-dark me-5" to="/">Our Products</router-link>
              </li>
              <li class="nav-item">
                <router-link class="nav-link text-dark me-5" to="/about">For Engineers</router-link>
              </li>
              <li class="nav-item">
                <router-link class="nav-link text-dark me-5" to="/contact">Multi-Vitamins</router-link>
              </li>
              <li>
                <router-link class="nav-link text-dark me-5" to="/contact">Buy</router-link>
              </li>

              <li class="nav-item">
                <router-link class="nav-link text-dark me-5" to="/contact">Books</router-link>
              </li>
              <li>
                <button class="btn btn-secondary">Sign in/Sign up</button>
              </li>
            </ul>
          </div>
          <!-- navbar ends here -->
        </div>
      </nav>
    </div>
  </div>
  <div class="row text-center mt-5">
    <div class="col-xl-6 col-md-12 col-sm-12">
      <h2 class="mt-5 me-5">
        LOOK AFTER THE PEOPLE,</h2> 
        <h2 class="ms-5">
        WHO LOOK AFTER YOUR BUSINESS.
      </h2>
      <h2 class="mt-5 fw-bolder">HEALTH WELLNESS.</h2>
      <button class="btn request-demo mt-4 p-2 px-4 text-white fw-bolder">REQUEST DEMO</button>
    </div>

    <div class="col-xl-6 col-md-12 col-sm-12 mt-5">
      <img class="person-img" src="@/assets/images/yoga-table.jpeg">
    </div>
  </div>
  <div class="row mt-3 text-center trusted-many">
    <h3 class="fw-bolder mt-4">TRUSTED BY MANY</h3>
    <div class="row mt-5 text-center d-flex justify-content-center pb-5 align-items-center">
      <div class="col-xl-2 col-md-3 col-sm-5 first-many p-4 px-5 ms-5">
        <h3 class="p-3"></h3>
      </div>
      <div class="col-xl-2 col-md-3 col-sm-5 second-many p-4 px-5 ms-5">
        <h3 class="p-3"></h3>
      </div>
      <div class="col-xl-2 col-md-3 col-sm-5 third-many p-4 px-5 ms-5">
        <h3 class="p-3"></h3>
      </div>
      <div class="col-xl-2 col-md-3 col-sm-5 fourth-many p-4 px-5 ms-5">
        <h3 class="p-3"></h3>
      </div>
    </div>
  </div>
  <div class="row mt-5 lifecycle-cost text-center">
    <div class="col-xl-12 col-md-12 col-sm-12">
      <h3 class="fw-bolder mt-4 text-dark">LIFECYCLE COST OF A DISEASE</h3>
    </div>
    <div class="row text-center mt-3 d-flex justify-content-center align-items-center">
      <div class="col-xl-2 col-md-12 col-sm-12">
        <div class="direct-cost rounded-4">
          <h3 class="text-white p-5">Direct Cost</h3>
        </div>
        <div class="mt-4">
          <h6 class=" ">Health care & medical cost</h6>
        </div>
      </div>
      <div class="col-xl-1 col-md-12 col-sm-12">+</div>
      <div class="col-xl-2 col-md-12 col-sm-12">
        <div class="indirect-cost rounded-4">
          <h3 class="text-white p-5">InDirect Cost</h3>
        </div>
        <div class="mt-4">
          <h6 class=" ">
            Decrease quality of life ,pain <br />
            anxiety ,inconvenience &
          </h6>
        </div>
      </div>
      <div class="col-xl-1 col-md-12 col-sm-12">+</div>
      <div class="col-xl-2 col-md-12 col-sm-12">
        <div class="intangible-cost rounded-4">
          <h3 class="text-white p-5">Intangible <br />Cost</h3>
        </div>
        <div class="mt-4">
          <h6 class=" ">
            Decrease quality of life ,pain <br />
            anxiety ,inconvenience &
          </h6>
        </div>
      </div>
      <div class="col-xl-1 col-md-12 col-sm-12">=</div>
      <div class="col-xl-2 col-md-12 col-sm-12">
        <div class="total-cost rounded-4">
          <h3 class="text-white p-5">Total Cost</h3>
        </div>
        <div class="mt-4">
          <h6 class=" ">
            Decrease quality of life ,pain <br />
            anxiety ,inconvenience &
          </h6>
        </div>
      </div>
    </div>
  </div>
  <div class="row text-center mt-5">
    <div class="col-xl-5 col-md-12 col-sm-12">
      <div class="natural">
        <hr class="line ms-5" />
        <div>
          <h2>
            WE HEAL YOU <br />
            NATURALLY
          </h2>
          <hr class="line ms-5" />
        </div>
      </div>
    </div>
    <div class="col-xl-7 col-md-12 col-sm-12">
      <div class="row ms-2 d-flex justify-content-around">
        <div class="col-xl-2 col-md-12 col-sm-12">
          <div class="rounded-2 bg-success">
            <img class="ayurvedic" src="@/assets/images/ayrvedha1.jpeg" alt="glass" />
          </div>
          <div class="mt-4">
            <h6 class=" ">Ayurveda</h6>
          </div>
        </div>
        <div class="col-xl-2 col-md-12 col-sm-12">
          <div class="rounded-2 bg-success">
            <!-- <h3 class="text-white p-5">Direct Cost</h3> -->
            <img class="ayurvedic" src="@/assets/images/homeopathy.jpeg" alt="" />
          </div>
          <div class="mt-4">
            <h6 class=" ">Homeopathy</h6>
          </div>
        </div>
        <div class="col-xl-2 col-md-12 col-sm-12">
          <div class="rounded-2 bg-success">
            <!-- <h3 class="text-white p-5">Direct Cost</h3> -->
            <img class="ayurvedic" src="@/assets/images/ayrvedha1.jpeg" alt="" />
          </div>
          <div class="mt-4">
            <h6 class=" ">Naturopathy</h6>
          </div>
        </div>
        <div class="col-xl-2 col-md-12 col-sm-12">
          <div class="rounded-2 bg-success">
            <!-- <h3 class="text-white p-5">Direct Cost</h3> -->
            <img class="ayurvedic" src="@/assets/images/homeopathy.jpeg" alt="" />
          </div>
          <div class="mt-4">
            <h6 class=" ">Yoga</h6>
          </div>
        </div>
      </div>
      <div class="row ms-2 d-flex justify-content-around mt-5">
        <div class="col-xl-2 col-md-12 col-sm-12">
          <div class="rounded-2 bg-success">
            <img class="ayurvedic" src="@/assets/images/ayrvedha1.jpeg" alt="" />
          </div>
          <div class="mt-4">
            <h6 class=" ">Meditation</h6>
          </div>
        </div>
        <div class="col-xl-2 col-md-12 col-sm-12">
          <div class="rounded-2 bg-success">
            <!-- <h3 class="text-white p-5">Direct Cost</h3> -->
            <img class="ayurvedic" src="@/assets/images/homeopathy.jpeg" alt="" />
          </div>
          <div class="mt-4">
            <h6 class=" ">physiotherapy</h6>
          </div>
        </div>
        <div class="col-xl-2 col-md-12 col-sm-12">
          <div class="rounded-2 bg-success">
            <!-- <h3 class="text-white p-5">Direct Cost</h3> -->
            <img class="ayurvedic" src="@/assets/images/ayrvedha1.jpeg" alt="" />
          </div>
          <div class="mt-4">
            <h6 class=" ">nutrition</h6>
          </div>
        </div>
        <div class="col-xl-2 col-md-12 col-sm-12">
          <div class="rounded-2 bg-success">
            <!-- <h3 class="text-white p-5">Direct Cost</h3> -->
            <img class="ayurvedic" src="@/assets/images/ayrvedha1.jpeg" alt="" />
          </div>
          <div class="mt-4">
            <h6 class=" ">Psychology</h6>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="row wellness">
    <div class="col-xl-6 col-md-12 col-sm-12">
      <h5 class="mt-4 ms-5 fw-bolder">HOLISTIC WELLNESS</h5>
      <h6 class="ms-5">NATURAL THERAPHIES IDENTIFY THE ROOT CAUSE</h6>
      <ul style="list-style-type: disc">
        <li class="ms-5 mt-4">
          <p>
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nobis aut eligendi dolor,
            facere quibusdam perspiciatis corporis hic tempora sed unde?
          </p>
        </li>
        <li class="ms-5">
          <p>
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nesciunt non voluptatibus
            dolorum nihil rerum molestias voluptate omnis quod nemo odio?
          </p>
        </li>
      </ul>
    </div>
    <div class="col-xl-6 col-md-12 col-sm-12">
      <h4 class="mt-5 ms-5 fw-bolder">6 DIMENSION OF WELNESS</h4>
      <div class="row mt-3 d-flex justify-content-start">
        <div class="col-xl-2 col-md-12 col-sm-12">
          <div class="rounded-2 spiritual">
            <img class="ayurvedic1 ms-4" src="@/assets/images/spiritual.jpeg" alt="" />
          </div>
          <div class="mt-4">
            <h6 class=" ">Spiritual</h6>
          </div>
        </div>
        <div class="col-xl-2 col-md-12 col-sm-12 ms-5">
          <div class="rounded-2 envoroment">
            <img class="ayurvedic1 ms-4" src="@/assets/images/environmental.jpeg" alt="" />
          </div>
          <div class="mt-4">
            <h6 class=" ">Environmental</h6>
          </div>
        </div>
        <div class="col-xl-2 col-md-12 col-sm-12 ms-5">
          <div class="rounded-2 emotional">
            <img class="ayurvedic1 ms-4" src="@/assets/images/emotional.jpeg" alt="" />
          </div>
          <div class="mt-4">
            <h6 class=" ">Emotional</h6>
          </div>
        </div>
      </div>
      <div class="row mt-3 d-flex justify-content-around">
        <div class=" col-xl-2 col-md-12 col-sm-12 me-5">
          <div class="rounded-2 spiritual">
            <img class="ayurvedic1 ms-4" src="@/assets/images/spiritual.jpeg" alt="" />
          </div>
          <div class="mt-4">
            <h6 class=" ">Spiritual</h6>
          </div>
        </div>
        <div class="col-xl-2 col-md-12 col-sm-12 me-5">
          <div class="rounded-2 bg-success">
            <img class="ayurvedic1 ms-4" src="@/assets/images/environmental.jpeg" alt="" />
          </div>
          <div class="mt-4">
            <h6 class=" ">Environmental</h6>
          </div>
        </div>
        <div class="col-xl-2 col-md-12 col-sm-12 me-5 ">
          <div class="rounded-2 emotional">
            <img class="ayurvedic1 ms-4" src="@/assets/images/emotional.jpeg" alt="" />
          </div>
          <div class="mt-4">
            <h6 class=" ">Emotional</h6>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="row text-center p-3 h-25">
    <div class="col-xl-12 col-md-12 col-sm-12"></div>
    <h1 class="text-dark">HEALTH PLAN</h1>
  </div>
  <!-- health plan -->
  <div class="row text-white ">
    <div class="col-xl-6 col-md-12 col-sm-12 heal heal-lorem">
      <h2 class="ms-3 text-success mt-5"> HEAL</h2>
      <ul style="list-style-type: disc">
        <li class="ms-3">
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Similique laborum expedita dolorum quod quo, sunt in
            vitae porro pariatur dolorem?</p>
        </li>
        <li class="ms-3">
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo molestiae qui ut beatae ipsam nesciunt fugiat
            iure accusantium fuga inventore!</p>
        </li>
        <li class="ms-3">
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo molestiae qui ut beatae ipsam nesciunt fugiat
            iure accusantium fuga inventore!</p>
        </li>
      </ul>
    </div>


    <div class="col-xl-6 col-md-12 col-sm-12 p-0 m-0">
      <img class="w-100 h-100" src="@/assets/images/yoga.jpeg" alt="">
    </div>
    <!-- 2nd image -->
    <div class="col-xl-6 col-md-12 col-sm-12 p-0 m-0">
      <img class="w-100 h-100" src="@/assets/images/doctor.jpeg" alt="">
    </div>
    <div class="col-xl-6 col-md-12 col-sm-12 text-dark heal-lorem">
      <h2 class="ms-3 text-success mt-5 ms-2"> ENGAGE</h2>
      <ul style="list-style-type: disc">
        <li class="ms-3">
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Similique laborum expedita dolorum quod quo, sunt in
            vitae porro pariatur dolorem?</p>
        </li>
        <li class="ms-3">
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo molestiae qui ut beatae ipsam nesciunt fugiat
            iure accusantium fuga inventore!</p>
        </li>
        <li class="ms-3">
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo molestiae qui ut beatae ipsam nesciunt fugiat
            iure accusantium fuga inventore!</p>
        </li>
      </ul>
    </div>
    <!-- 3RD image -->



    <div class="col-xl-6 col-md-12 col-sm-12 heal heal-lorem">
      <h2 class="ms-3 text-success mt-5 ms-2">STAY FIT</h2>
      <ul style="list-style-type: disc">
        <li class="ms-3">
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Similique laborum expedita dolorum quod quo, sunt in
            vitae porro pariatur dolorem?</p>
        </li>
        <li class="ms-3">
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo molestiae qui ut beatae ipsam nesciunt fugiat
            iure accusantium fuga inventore!</p>
        </li>
        <li class="ms-3">
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo molestiae qui ut beatae ipsam nesciunt fugiat
            iure accusantium fuga inventore!</p>
        </li>
      </ul>
    </div>
    <div class="col-xl-6 col-md-12 col-sm-12 p-0 m-0">
      <img class="w-100 h-100" src="@/assets/images/nature.jpeg" alt="">
    </div>
  </div>
  <!-- // work -->

  <div class="row text-center">
    <div class="col-xl-12 col-md-12 col-sm-12 fw-bolder mt-5 h4"> HOW DOES THIS WORK?</div>
    <div class="col-xl-12">
      <span class="text-warning h5 mt-3">Step 2</span>
      <p class="h6 mt-2">Lorem ipsum dolor consectetur <br />adipisicing elit. Adipisci Incidunt iusto <br />consequatur
        iure deleniti mollitia?</p>

    </div>
    <div class="col-xl-4 col-md-12 col-sm-12">
      <div class="col-xl-12">
        <span class="text-warning h5 mt-3">Step 1</span>
        <p class="h6 mt-2">Lorem ipsum dolor consectetur <br />adipisicing elit. Adipisci Incidunt iusto <br />consequatur
          iure deleniti mollitia?</p>
      </div>

    </div>
    <div class="col-xl-4 col-md-12 col-sm-12">
      <p class="h6 mt-2">Lorem ipsum dolor consectetur <br />adipisicing elit. Adipisci Incidunt iusto </p>
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT30hpqd_Ac5ct7fXYKntczKCTlFlNSq15P6A&usqp=CAU"
        alt="">
    </div>
    <div class="col-xl-4 col-md-12 col-sm-12">
      <div class="col-xl-12">
        <span class="text-warning h5 mt-3">Step 3</span>
        <p class="h6 mt-2">Lorem ipsum dolor consectetur <br />adipisicing elit. Adipisci Incidunt iusto <br />consequatur
          iure deleniti mollitia?</p>
        <button class="btn request-demo p-2 px-3 mt-4">REQUEST DEMO</button>
      </div>
    </div>

  </div>

  <!-- offer -->
  <div class="row mt-5 text-center">
    <div class="col-xl-12 col-md-12 col-sm-12  h4">WHAT WE OFFER
    </div>
    <div class="row mt-3 d-flex justify-content-around">
      <div class="col-xl-3 col-md-12 col-sm-12">1

        <div class="d-flex">
          <div class="offer ms-5">
            <img class="we-offer" src="@/assets/images/career.jpeg" alt="" />
          </div>
          <p class="d-flex align-items-center ms-3">Lorem ipsum</p>
        </div>
      </div>
      <div class="col-xl-3 col-md-12 col-sm-12  h6">2
        <div class="d-flex ms-5">
          <div class="offer ">
            <img class="we-offer" src="@/assets/images/pyramid.jpeg" alt="" />
          </div>
          <p class="d-flex align-items-center ms-3">Lorem ipsum</p>

        </div>

      </div>
      <div class="col-xl-3 col-md-12 col-sm-12  h6">3
        <div class="d-flex ms-5">
          <div class="offer">
            <img class="we-offer" src="@/assets/images/doctorimg.jpeg" alt="" />
          </div>
          <p class="d-flex align-items-center ms-3">Lorem ipsum</p>

        </div>

      </div>
      <div class="col-xl-3 col-md-12 col-sm-12">4
        <div class="d-flex ms-5">
          <div class="offer">
            <img class="we-offer" src="@/assets/images/career.jpeg" alt="" />
          </div>
          <p class="d-flex align-items-center ms-3">Lorem ipsum</p>
        </div>
      </div>
    </div>
    <div class="row mt-3 d-flex justify-content-around">
      <div class="col-xl-3 col-md-12 col-sm-12">1

        <div class="d-flex">
          <div class="offer ms-5">
            <img class="we-offer" src="@/assets/images/career.jpeg" alt="" />
          </div>
          <p class="d-flex align-items-center ms-3">lorem ipsum</p>
        </div>
      </div>
      <div class="col-xl-3 col-md-12 col-sm-12  h6">2
        <div class="d-flex ms-5">
          <div class="offer ">
            <img class="we-offer" src="@/assets/images/pyramid.jpeg" alt="" />
          </div>
          <p class="d-flex align-items-center ms-3">lorem ipsum</p>

        </div>

      </div>
      <div class="col-xl-3 col-md-12 col-sm-12  h6">3
        <div class="d-flex ms-5">
          <div class="offer">
            <img class="we-offer" src="@/assets/images/pyramid.jpeg" alt="" />
          </div>
          <p class="d-flex align-items-center ms-3">Lorem ipsum</p>

        </div>

      </div>
      <div class="col-xl-3 col-md-12 col-sm-12">4
        <div class="d-flex ms-5">
          <div class="offer">
            <img class="we-offer" src="@/assets/images/pyramid.jpeg" alt="" />
          </div>
          <p class="d-flex align-items-center ms-3">Lorem ipsum</p>
        </div>
      </div>
    </div>
    <div class="row mt-3 d-flex justify-content-around">
      <div class="col-xl-3 col-md-12 col-sm-12">1

        <div class="d-flex">
          <div class="offer ms-5">
            <img class="we-offer" src="@/assets/images/career.jpeg" alt="" />
          </div>
          <p class="d-flex align-items-center ms-3">Lorem ipsum</p>
        </div>
      </div>
      <div class="col-xl-3 col-md-12 col-sm-12  h6">2
        <div class="d-flex ms-5">
          <div class="offer ">
            <img class="we-offer" src="@/assets/images/doctorimg.jpeg" alt="" />
          </div>
          <p class="d-flex align-items-center ms-3">Lorem ipsum</p>

        </div>

      </div>
      <div class="col-xl-3 col-md-12 col-sm-12  h6">3
        <div class="d-flex ms-5">
          <div class="offer">
            <img class="we-offer" src="@/assets/images/career.jpeg" alt="" />
          </div>
          <p class="d-flex align-items-center ms-3">Lorem ipsum</p>
        </div>

      </div>
      <div class="col-xl-3 col-md-12 col-sm-12">4
        <div class="d-flex ms-5">
          <div class="offer">
          </div>
        </div>
      </div>
    </div>

  </div>
  <div class="row mt-3 text-center text-white">
    <div class="col-xl-6 col-md-12 col-sm-12 laptop-img">
    </div>
    <div class="col-xl-6 col-md-12 col-sm-12 DASHBOARD-complete ">
      <h3 class="text-white mt-4">COMPLETE <br /> DASHBOARD FOR <br /> YOUR COMPANY </h3>
      <button class="btn request-demo mt-5 p-2 px-3 mb-4">REQUEST DEMO</button>
    </div>
  </div>
  <div class="col-xl-12 col-md-12 col-sm-12 mt-5 h4">
    <img class="mt-0 rounded mx-auto d-block " src="@/assets/images/lapy.jpeg" alt="" />
  </div>

  <div class="row mt-2 p-2">
  </div>
  <div class="row text-center footer text-white">
    <div class="col-xl-3 col-md-6 col-sm-12">
      <h4 class="text-white mt-3"> Reach Out to Us</h4>
      <h5 class=" mt-1"> Lorem epsum pvt ltd.</h5>
      <p class="mt-4 ms-3">Lorem ipsum dolor consecteturLorem ipsum dolor consecteturLorem ipsum dolor consectetur</p>
      <span class="text-white">+919966564657</span>
      <br />
      <span class="text-white">vamsi01@gamil.com</span>
    </div>
    <div class="col-xl-2 col-md-6 col-sm-12 mt-5 ">
      <h5> About</h5>
      <h6> Contact Us</h6>
      <h6 class="me-2"> About Us</h6>
      <h6 class="me-3"> Careers</h6>
      <h6 class="me-4"> Blogs</h6>
      <h6 class="me-2"> Sitemap</h6>
      <h6 class="ms-3"> Map Account</h6>
    </div>
    <div class="col-xl-2 col-md-6 col-sm-12 mt-4">
      <h5 class="fw-bolder mt-3">Policy Info</h5>
      <h6>Privacy Policy</h6>
      <h6>Terms of Use</h6>
      <h6>Return Policy</h6>
    </div>
    <div class="col-xl-2 col-md-6 col-sm-12 mt-4">
      <h5 class="fw-bolder mt-3">Need Help?</h5>
      <h6 class="me-5">FAQs</h6>
      <h6>Online Support</h6>
      <h6>Customer support</h6>
      <button class="btn request-demo mt-5 p-2 px-3 mb-4 mt-4">REQUEST DEMO</button>
    </div>
    <div class="col-xl-3 col-md-6 col-sm-12 mt-4">
      <h5 class="fw-bolder mt-3">Subscribe Our Newsletter</h5>
      <div class="input-group mb-3">
        <input type="text" class="form-control" placeholder="Enter Your Email" aria-label="Recipient's username"
          aria-describedby="basic-addon2">
        <span class="input-group-text" id="basic-addon2">
          <img class="input-email" src="@/assets/images/arrow.jpeg" alt="" />
        </span>
      </div>
      <p class="mt-2">Register now to get upfates on promotions and coupons or download App</p>
    </div>

    <div class="row m-3">
  <h4 class="copyright-code">&copy;copyright 2021 unitecode</h4>
</div>


  </div>
</template>

<style>
.navbar-head {
  border: 2px solid black;
  background-color: #fff;
}

.laptop-img {
  background-color: #003333;
}
.copyright-code{
  margin-left: 400px;
}

.person-img {
  width: 500px;
  height: 400px;
  margin-top: 59px;
}

.trusted-many {
  gap: 50px;
  background-color: rgb(243, 211, 150);
}


.direct-cost {
  background-image: url('data:image/jpeg;base64,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');

}

.indirect-cost {
  background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRS1vyst52LFKisPxZ6Qw0-KR7rCMD1xEdluQ&usqp=CAU');

  border-radius: 30px;
}

.intangible-cost {
  background-image: url('https://i.pinimg.com/originals/e7/9e/69/e79e695e15c02fedea44e9edb7dc9023.png');

}

.total-cost {
  background-image: url('data:image/jpeg;base64,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');
  border-radius: 30px;
}

hr.line {
  border-top: 8px solid orange;
}

.ayurvedic {
  width: 57px;
  height: 132px;
  padding: 10px;
}

.ayurvedic1 {
  width: 47px;
  height: 99px;
  padding: 13px;
}

.envoroment {
  background-color: rgb(33, 91, 33);
}

.spiritual {
  background-color: rgb(58, 19, 58);

}

.emotional {
  background-color: rgb(174, 116, 7);
}

.natural {
  margin-top: 100px;
}

.wellness {
  background-color: rgb(228, 228, 168);
}

.heal {
  background-color: rgb(30, 39, 30);
}

.offer {
  background-color: rgb(182, 222, 121);
}

.we-offer {
  width: 100px;
  height: 50px
}

.we-offer {
  width: 122px;
  height: 99px;
  padding: 13px;
}

.DASHBOARD-complete {
  background-color: rgb(19, 19, 20);
}

.footer {
  background-color: #003333;
}

.second-many {
  background-color: orange;
}

.third-many {
  background-color: rgb(43, 141, 43);
}

.fourth-many {
  background-color: rgb(54, 26, 54);
}

.first-many {
  background-color: rgb(29, 89, 112);
}

.request-demo {
  background-color: #FF8000;
}

.input-email {
  width: 40px;
  height: 40px;
}
</style>