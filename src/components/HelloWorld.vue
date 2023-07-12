<template>
  <div class="about">
    <div class="block header-div">
      <nav
        class="navbar navbar-expand-sm text-white col-xl-12 col-md-12 col-sm-12 navbar-head shadow-lg p-4"
      >
        <div class="container-fluid">
          <button
            class="navbar-toggler text-white bg-white"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarTogglerDemo03"
            aria-controls="navbarTogglerDemo03"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <!-- <img
            class="navbar-brand text-danger logo-image"
            src="data:image/jpeg;base64,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"
          /> -->
          <div class="collapse navbar-collapse" id="navbarTogglerDemo03">
            <ul class="navbar-nav ms-auto">
              <!-- <button class="c-name btn btn-sucess"> Srikanth O- farms(logo)</button>  -->
              <li class="nav-item">
                <!-- <a class="nav-link text-white" href="#">Home</a> -->
                <router-link class="nav-link text-dark" to="/" exact>Our Products</router-link>
              </li>
              <li class="nav-item">
                <!-- <a class="nav-link text-white" href="#"> Contact</a> -->
                <router-link class="nav-link text-dark" to="/about">For Engineers</router-link>
              </li>
              <li class="nav-item">
                <!-- <a class="nav-link text-white" href="#"> Contact</a> -->
                <router-link class="nav-link text-dark" to="/contact">Multi-Vitamins</router-link>
              </li>

              <li>
                <router-link class="nav-link text-white" to="/life"> Buy</router-link>
              </li>

              <li class="nav-item">
                <!-- <a class="nav-link text-white" href="#"> Contact</a> -->
                <router-link class="nav-link text-dark" to="/contact">Books</router-link>
              </li>

              <li>
                <button class="btn btn-secondary">Sign in/Sign up</button>
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </div>
  </div>
  <div class="row text-center mt-5">
    <div class="col-xl-6 col-md-12 col-sm-12">
      <h2 class="mt-5">
        LOOK AFTER THE PEOPLE <br />
        WHO LOOK AFTER YOUR BUSINESS
      </h2>
      <h2 class="mt-5 fw-bolder">HEALTH WELLNESS</h2>
      <button class="btn btn-warning mt-4 p-2 px-4 text-white fw-bolder">REQUEST DEMO</button>
    </div>

    <div class="col-xl-6 col-md-12 col-sm-12 mt-5">
      <img
        class="person-img"
        src="data:image/jpeg;base64,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"
      />
    </div>
  </div>
  <div class="row mt-3 text-center bg-warning">
    <h3 class="fw-bolder mt-4">TRUSTED BY MANY</h3>
    <div class="row mt-5 text-center d-flex justify-content-center pb-5 align-items-center">
      <div class="col-xl-2 col-md-3 col-sm-5 bg-dark p-4 px-5 ms-5">
        <h3>1</h3>
      </div>
      <div class="col-xl-2 col-md-3 col-sm-5 bg-danger p-4 px-5 ms-5">
        <h3>2</h3>
      </div>
      <div class="col-xl-2 col-md-3 col-sm-5 bg-success p-4 px-5 ms-5">
        <h3>3</h3>
      </div>
      <div class="col-xl-2 col-md-3 col-sm-5 bg-white p-4 px-5 ms-5">
        <h3>4</h3>
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
        <div class="mt-4"><h6 class=" ">Health care & medical cost</h6></div>
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
            <img
              class="ayurvedic"
              src="@/assets/images/glass2.jpeg"
              alt="glass"
            />
          </div>
          <div class="mt-4"><h6 class=" ">Ayurveda</h6></div>
        </div>
        <div class="col-xl-2 col-md-12 col-sm-12">
          <div class="rounded-2 bg-success">
            <!-- <h3 class="text-white p-5">Direct Cost</h3> -->
            <img
              class="ayurvedic"
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTezB1Orbd_0o8KQGBPfRvdotSsZOJUYmbExA&usqp=CAU"
              alt=""
            />
          </div>
          <div class="mt-4"><h6 class=" ">Homeopathy</h6></div>
        </div>
        <div class="col-xl-2 col-md-12 col-sm-12">
          <div class="rounded-2 bg-success">
            <!-- <h3 class="text-white p-5">Direct Cost</h3> -->
            <img
              class="ayurvedic"
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTezB1Orbd_0o8KQGBPfRvdotSsZOJUYmbExA&usqp=CAU"
              alt=""
            />
          </div>
          <div class="mt-4"><h6 class=" ">Naturopathy</h6></div>
        </div>
        <div class="col-xl-2 col-md-12 col-sm-12">
          <div class="rounded-2 bg-success">
            <!-- <h3 class="text-white p-5">Direct Cost</h3> -->
            <img
              class="ayurvedic"
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTezB1Orbd_0o8KQGBPfRvdotSsZOJUYmbExA&usqp=CAU"
              alt=""
            />
          </div>
          <div class="mt-4"><h6 class=" ">Yoga</h6></div>
        </div>
      </div>
      <div class="row ms-2 d-flex justify-content-around mt-5">
        <div class="col-xl-2 col-md-12 col-sm-12">
          <div class="rounded-2 bg-success">
            <img
              class="ayurvedic"
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTezB1Orbd_0o8KQGBPfRvdotSsZOJUYmbExA&usqp=CAU"
              alt=""
            />
          </div>
          <div class="mt-4"><h6 class=" ">Meditation</h6></div>
        </div>
        <div class="col-xl-2 col-md-12 col-sm-12">
          <div class="rounded-2 bg-success">
            <!-- <h3 class="text-white p-5">Direct Cost</h3> -->
            <img
              class="ayurvedic"
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTezB1Orbd_0o8KQGBPfRvdotSsZOJUYmbExA&usqp=CAU"
              alt=""
            />
          </div>
          <div class="mt-4"><h6 class=" ">physiotherapy</h6></div>
        </div>
        <div class="col-xl-2 col-md-12 col-sm-12">
          <div class="rounded-2 bg-success">
            <!-- <h3 class="text-white p-5">Direct Cost</h3> -->
            <img
              class="ayurvedic"
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTezB1Orbd_0o8KQGBPfRvdotSsZOJUYmbExA&usqp=CAU"
              alt=""
            />
          </div>
          <div class="mt-4"><h6 class=" ">nutrition</h6></div>
        </div>
        <div class="col-xl-2 col-md-12 col-sm-12">
          <div class="rounded-2 bg-success">
            <!-- <h3 class="text-white p-5">Direct Cost</h3> -->
            <img
              class="ayurvedic"
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTezB1Orbd_0o8KQGBPfRvdotSsZOJUYmbExA&usqp=CAU"
              alt=""
            />
          </div>
          <div class="mt-4"><h6 class=" ">Psychology</h6></div>
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
            <img
              class="ayurvedic1 ms-4"
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTezB1Orbd_0o8KQGBPfRvdotSsZOJUYmbExA&usqp=CAU"
              alt=""
            />
          </div>
          <div class="mt-4"><h6 class=" ">Ayurveda1</h6></div>
        </div>
        <div class="col-xl-2 col-md-12 col-sm-12 ms-5">
          <div class="rounded-2 envoroment">
            <img
            class="ayurvedic1 ms-4"
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTezB1Orbd_0o8KQGBPfRvdotSsZOJUYmbExA&usqp=CAU"
              alt=""
            />
          </div>
          <div class="mt-4"><h6 class=" ">Ayurveda2</h6></div>
        </div>
        <div class="col-xl-2 col-md-12 col-sm-12 ms-5">
          <div class="rounded-2 emotional">
            <img
            class="ayurvedic1 ms-4"
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTezB1Orbd_0o8KQGBPfRvdotSsZOJUYmbExA&usqp=CAU"
              alt=""
            />
          </div>
          <div class="mt-4"><h6 class=" ">Ayurveda3</h6></div>
        </div>
      </div>
      <div class="row mt-3 d-flex justify-content-around">
        <div class=" col-xl-2 col-md-12 col-sm-12 me-5">
          <div class="rounded-2 spiritual">
            <img
            class="ayurvedic1 ms-4"
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTezB1Orbd_0o8KQGBPfRvdotSsZOJUYmbExA&usqp=CAU"
              alt=""
            />
          </div>
          <div class="mt-4"><h6 class=" ">Ayurved4</h6></div>
        </div>
        <div class="col-xl-2 col-md-12 col-sm-12 me-5">
          <div class="rounded-2 bg-success">
            <img
            class="ayurvedic1 ms-4"
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTezB1Orbd_0o8KQGBPfRvdotSsZOJUYmbExA&usqp=CAU"
              alt=""
            />
          </div>
          <div class="mt-4"><h6 class=" ">Ayurveda5</h6></div>
        </div>
        <div class="col-xl-2 col-md-12 col-sm-12 me-5 ">
          <div class="rounded-2 emotional">
            <img
            class="ayurvedic1 ms-4"
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTezB1Orbd_0o8KQGBPfRvdotSsZOJUYmbExA&usqp=CAU"
              alt=""
            />
          </div>
          <div class="mt-4"><h6 class=" ">Ayurved6</h6></div>
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
  <h2 class="ms-3 text-success mt-3"> HEAL</h2>
  <ul style="list-style-type: disc">
    <li class="ms-3" ><p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Similique laborum expedita dolorum quod quo, sunt in vitae porro pariatur dolorem?</p></li>
    <li class="ms-3" ><p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo molestiae qui ut beatae ipsam nesciunt fugiat iure accusantium fuga inventore!</p></li>
    <li class="ms-3" ><p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo molestiae qui ut beatae ipsam nesciunt fugiat iure accusantium fuga inventore!</p></li>
  </ul>
    </div>
     
 
  <div class="col-xl-6 col-md-12 col-sm-12 p-0 m-0">
    <img  class="w-100 h-100" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRUeIuYlPkF-_0OKZ44e-D1smXseX-xbAHVIA&usqp=CAU" alt="">
  </div>
 <!-- 2nd image -->
 <div class="col-xl-6 col-md-12 col-sm-12 p-0 m-0">
    <img  class="w-100 h-100" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRUeIuYlPkF-_0OKZ44e-D1smXseX-xbAHVIA&usqp=CAU" alt="">
  </div>
  <div class="col-xl-6 col-md-12 col-sm-12 text-dark heal-lorem">
  <h2 class="ms-3 text-success mt-3"> ENGAGE</h2>
  <ul style="list-style-type: disc">
    <li class="ms-3" ><p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Similique laborum expedita dolorum quod quo, sunt in vitae porro pariatur dolorem?</p></li>
    <li class="ms-3" ><p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo molestiae qui ut beatae ipsam nesciunt fugiat iure accusantium fuga inventore!</p></li>
    <li class="ms-3" ><p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo molestiae qui ut beatae ipsam nesciunt fugiat iure accusantium fuga inventore!</p></li>
  </ul>
    </div>
    <!-- 3RD image -->
   
 
 
    <div class="col-xl-6 col-md-12 col-sm-12 heal heal-lorem">
  <h2 class="ms-3 text-success mt-3"> HEAL</h2>
  <ul style="list-style-type: disc">
    <li class="ms-3" ><p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Similique laborum expedita dolorum quod quo, sunt in vitae porro pariatur dolorem?</p></li>
    <li class="ms-3" ><p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo molestiae qui ut beatae ipsam nesciunt fugiat iure accusantium fuga inventore!</p></li>
    <li class="ms-3" ><p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo molestiae qui ut beatae ipsam nesciunt fugiat iure accusantium fuga inventore!</p></li>
  </ul>
    </div>
    <div class="col-xl-6 col-md-12 col-sm-12 p-0 m-0">
    <img  class="w-100 h-100" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSyEv5NHJKdCBo_Bo2Ux17XS460gIpNhqJ54A&usqp=CAU" alt="">
  </div>  
</div>
<!-- // work -->

<div class="row text-center">
  <div class="col-xl-12 col-md-12 col-sm-12 fw-bolder mt-5 h4"> HOW DOES THIS WORK?</div>
  <div class="col-xl-12">
    <span class="text-warning h5 mt-3">Step 2</span>
    <p class="h6 mt-2">Lorem ipsum dolor  consectetur <br/>adipisicing elit. Adipisci Incidunt iusto <br/>consequatur iure deleniti  mollitia?</p>
   
  </div>
  <div class="col-xl-4 col-md-12 col-sm-12">
    <div class="col-xl-12">
    <span class="text-warning h5 mt-3">Step 1</span>
    <p class="h6 mt-2">Lorem ipsum dolor  consectetur <br/>adipisicing elit. Adipisci Incidunt iusto <br/>consequatur iure deleniti  mollitia?</p>
  </div>
 
  </div>
  <div class="col-xl-4 col-md-12 col-sm-12">
    <p class="h6 mt-2">Lorem ipsum dolor  consectetur <br/>adipisicing elit. Adipisci Incidunt iusto </p>
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT30hpqd_Ac5ct7fXYKntczKCTlFlNSq15P6A&usqp=CAU" alt="">
  </div>
  <div class="col-xl-4 col-md-12 col-sm-12">
    <div class="col-xl-12">
    <span class="text-warning h5 mt-3">Step 3</span>
    <p class="h6 mt-2">Lorem ipsum dolor  consectetur <br/>adipisicing elit. Adipisci Incidunt iusto <br/>consequatur iure deleniti  mollitia?</p>
    <button class="btn btn-warning p-2 px-3 mt-4">REQUEST DEMO</button>
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
              <img
              class="we-offer"
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTezB1Orbd_0o8KQGBPfRvdotSsZOJUYmbExA&usqp=CAU"
              alt=""
            />
            </div>
            <p class="d-flex align-items-center ms-3">lorem ipsum</p>  
          </div>
      </div>
      <div class="col-xl-3 col-md-12 col-sm-12  h4">2
        <div class="d-flex ms-5">
            <div class="offer ">
              <img
              class="we-offer"
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTezB1Orbd_0o8KQGBPfRvdotSsZOJUYmbExA&usqp=CAU"
              alt=""
            />
            </div>
            <p class="d-flex align-items-center ms-3">lorem ipsum</p>
             
          </div>
         
      </div>
      <div class="col-xl-3 col-md-12 col-sm-12  h4">3
        <div class="d-flex ms-5">
            <div class="offer">
              <img
              class="we-offer"
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTezB1Orbd_0o8KQGBPfRvdotSsZOJUYmbExA&usqp=CAU"
              alt=""
            />
            </div>
            <p class="d-flex align-items-center ms-3">lorem ipsum</p>
             
          </div>
         
      </div>
      <div class="col-xl-3 col-md-12 col-sm-12">4
        <div class="d-flex ms-5">
            <div class="offer">
              <img
              class="we-offer"
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTezB1Orbd_0o8KQGBPfRvdotSsZOJUYmbExA&usqp=CAU"
              alt=""
            />
            </div>
            <p class="d-flex align-items-center ms-3">lorem ipsum</p>
          </div>
      </div>
      </div>
      <div class="row mt-3 d-flex justify-content-around">
        <div class="col-xl-3 col-md-12 col-sm-12">1
         
          <div class="d-flex">
            <div class="offer ms-5">
              <img
              class="we-offer"
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTezB1Orbd_0o8KQGBPfRvdotSsZOJUYmbExA&usqp=CAU"
              alt=""
            />
            </div>
            <p class="d-flex align-items-center ms-3">lorem ipsum</p>  
          </div>
      </div>
      <div class="col-xl-3 col-md-12 col-sm-12  h4">2
        <div class="d-flex ms-5">
            <div class="offer ">
              <img
              class="we-offer"
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTezB1Orbd_0o8KQGBPfRvdotSsZOJUYmbExA&usqp=CAU"
              alt=""
            />
            </div>
            <p class="d-flex align-items-center ms-3">lorem ipsum</p>
             
          </div>
         
      </div>
      <div class="col-xl-3 col-md-12 col-sm-12  h4">3
        <div class="d-flex ms-5">
            <div class="offer">
              <img
              class="we-offer"
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTezB1Orbd_0o8KQGBPfRvdotSsZOJUYmbExA&usqp=CAU"
              alt=""
            />
            </div>
            <p class="d-flex align-items-center ms-3">lorem ipsum</p>
             
          </div>
         
      </div>
      <div class="col-xl-3 col-md-12 col-sm-12">4
        <div class="d-flex ms-5">
            <div class="offer">
              <img
              class="we-offer"
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTezB1Orbd_0o8KQGBPfRvdotSsZOJUYmbExA&usqp=CAU"
              alt=""
            />
            </div>
            <p class="d-flex align-items-center ms-3">lorem ipsum</p>
          </div>
      </div>
      </div>
      <div class="row mt-3 d-flex justify-content-around">
        <div class="col-xl-3 col-md-12 col-sm-12">1
         
          <div class="d-flex">
            <div class="offer ms-5">
              <img
              class="we-offer"
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTezB1Orbd_0o8KQGBPfRvdotSsZOJUYmbExA&usqp=CAU"
              alt=""
            />
            </div>
            <p class="d-flex align-items-center ms-3">lorem ipsum</p>  
          </div>
      </div>
      <div class="col-xl-3 col-md-12 col-sm-12  h4">2
        <div class="d-flex ms-5">
            <div class="offer ">
              <img
              class="we-offer"
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTezB1Orbd_0o8KQGBPfRvdotSsZOJUYmbExA&usqp=CAU"
              alt=""
            />
            </div>
            <p class="d-flex align-items-center ms-3">lorem ipsum</p>
             
          </div>
         
      </div>
      <div class="col-xl-3 col-md-12 col-sm-12  h4">3
        <div class="d-flex ms-5">
            <div class="offer">
              <img
              class="we-offer"
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTezB1Orbd_0o8KQGBPfRvdotSsZOJUYmbExA&usqp=CAU"
              alt=""
            />
            </div>
            <p class="d-flex align-items-center ms-3">lorem ipsum</p>
             
          </div>
         
      </div>
      <div class="col-xl-3 col-md-12 col-sm-12">4
        <div class="d-flex ms-5">
            <div class="offer">
              <!-- <img
              class="we-offer"
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTezB1Orbd_0o8KQGBPfRvdotSsZOJUYmbExA&usqp=CAU"
              alt=""
            /> -->
            </div>
            <!-- <p class="d-flex align-items-center ms-3">lorem ipsum</p> -->
          </div>
      </div>
      </div>

</div>
<div class="row mt-3 text-center text-white">
  <div class="col-xl-6 col-md-12 col-sm-12">
<!-- <h4>heloooooooooooooo</h4> -->
<button class="btn btn-warning mt-5 p-2 px-3">lap pic</button>
     
  </div>
  <div class="col-xl-6 col-md-12 col-sm-12 DASHBOARD-complete ">
    <h3 class="text-white mt-4">COMPLETE <br/> DASHBOARD FOR <br/> YOUR COMPANY </h3>
    <button class="btn btn-warning mt-5 p-2 px-3 mb-4">REQUEST DEMO</button>
  </div>
</div>
<div class="row mt-2 p-5">
hhh
</div>
<div class="row text-center footer text-white">
  <div class="col-xl-3 col-md-6 col-sm-12">
     <h3 class="text-white mt-3 fw-bolder"> Reach out to Us</h3>
     <h4 class=" mt-1"> lorem epsum pvt ltd</h4>
     <p class="mt-1 ms-3">Lorem ipsum dolor  consecteturLorem ipsum dolor  consecteturLorem ipsum dolor  consectetur</p>
     <span class="text-white">*999999999</span>
     <span class="text-white">vamsi01@gamil.com</span>
  </div>
  <div class="col-xl-2 col-md-6 col-sm-12">
     <h4> About</h4>
     <h4> Contact Us</h4>
     <h4> About</h4>
     <h4> About</h4>

    </div>
    <div class="col-xl-2 col-md-6 col-sm-12">
     <h4 class="fw-bolder mt-3">policy info</h4>
     <h5>privacy policy</h5>
     <h5>privacy policy</h5>
     <h5>privacy policy</h5>
     <h5>privacy policy</h5>
    </div>
    <div class="col-xl-2 col-md-6 col-sm-12">
      <h4 class="fw-bolder mt-3">NEED HEKP?</h4>
     <h5>privacy policy</h5>
     <h5>privacy policy</h5>
     <h5>privacy policy</h5>
     <button class="btn btn-warning mt-5 p-2 px-3 mb-4 mt-4">REQUEST DEMO</button>
    </div>
    <div class="col-xl-3 col-md-6 col-sm-12">
      <h4 class="fw-bolder mt-3">Subscribe Our Newsletter</h4>
      <p class="mt-2">Register now to get upfates on promotions and coupons or download App</p>
    </div>

    <div class="row m-3 float-end">
<h4 class=""> &copy;copyright 2021 unitecode</h4>
    </div>

</div>

</template>

<style>
/* @media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
} */

.navbar-head {
  border: 2px solid black;
  background-color: #fff;
}

.person-img {
  width: 500px;
  height: 400px;
  margin-top: 59px;
}
.trusted-many {
  gap: 50px;
}
/* .lifecycle-cost{
  color:#ad4b4b
} */
.direct-cost {
  background-image: url('data:image/jpeg;base64,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');
  /* width: 214px;
  height: 150px; */
}
.indirect-cost {
  background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRS1vyst52LFKisPxZ6Qw0-KR7rCMD1xEdluQ&usqp=CAU');
  /* width: 214px;
  height: 150px; */
  border-radius: 30px;
}
.intangible-cost {
  background-image: url('https://i.pinimg.com/originals/e7/9e/69/e79e695e15c02fedea44e9edb7dc9023.png');
  /* width: 214px;
  height: 150px; */
}
.total-cost {
  background-image: url('data:image/jpeg;base64,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');
  /* width: 214px;
  height: 150px; */
  border-radius: 30px;
}
hr.line {
  /* color:orange;
  font-size: 30px; */
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
.envoroment{
  background-color: rgb(33, 91, 33);
}
.spiritual{
  background-color:rgb(58, 19, 58);

}
.emotional{
  background-color: rgb(174, 116, 7);
}
.natural {
  margin-top: 100px;
}
.wellness {
  background-color: rgb(228, 228, 168);
}
.heal{
  background-color:rgb(30, 39, 30);
}
.offer{
  background-color: rgb(182, 222, 121);
}
.we-offer{
  width:100px;
  height:50px

}
.we-offer {
    width: 122px;
    height: 99px;
    padding: 13px;
}
.DASHBOARD-complete{
  background-color:rgb(33, 33, 54);
}
.footer{
  background-color:rgb(35, 35, 46);
}
/* .heal{
  width:100%;
  height:60%
} */
/* .heal-yoga{
  width:100%;
  height:50%
} */
/* .heal-lorem{
  width:100%;
 
} */
</style>hhh