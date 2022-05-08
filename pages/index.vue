<template>
  <div>

    <div class="d-none d-xl-block position-absolute bg-image w-100 h-100" style="z-index: -1;">
        <!-- <img src="/image-hero-desktop.png" alt=""> -->
    </div>


    <div class="container py-4">
      <div class="row">
        <div class="d-flex justify-content-between">
          <div>
          <img src="/logo-dark.svg" alt="">
          </div>
          <button class="btn btn-primary border-0 bg-pink-gradient py-2 px-4">
            Get Started
          </button>
        </div>
      </div>
    </div>

    <div class="container mt-5 pt-5 pb-md-5" style="min-height: 500px;">
      <div class="row">
        <div class="col-md-12 pb-5">
          <h1>
          Maximize skill, <br>
          minimize budget
          </h1>

          <br><br>

          <span class="text-body">
          Our modern courses across a range of in-demand <br>
          skills will give you the knowledge you need to live the life you want.
          </span>
          <br><br>
        
          <button class="btn btn-primary rounded border-0 bg-pink-gradient py-2 px-4">
            Get Started
          </button>
        </div>
      </div>
    </div>


    <div class="d-md-none w-100">
      <img src="/image-hero-mobile-fixed.svg" class="w-100" alt="">
    </div>

    <div class="bg-linear-gradient mt-md-5 pb-5">
      <div class="container">
        <div class="row gx-4">
          <div class="col-md-4 mt-md-5 mb-2 py-4">
            <div class="p-4 py-5 h-100 bg-white text-white bg-pink-gradient rounded">
              <h3>
                Check out our most popular courses!
              </h3>
            </div>
          </div>
          <div class="col-md-4 mt-5 mb-2 py-4">
            <div class="ps-5 position-relative">
              <div class="ps-5 position-absolute top-0 start-0 translate-middle">
                <img class="ps-5" src="/icon-animation.svg" alt="">
              </div>
            </div>
            <div class="p-4 py-5 bg-white rounded">
              <h4 class="pb-3">
                Animation
              </h4> 

              <span class="text-body">
                Learn the latest animation techniques to create stunning motion design and captivate your audience.
              </span>

              <br><br>
              <span class="text-pink fw-bold">
                Get Started
              </span>
            </div>
          </div>
          <div class="col-md-4 mt-5 mb-2 py-4">
            <div class="position-relative">
              <div class="ps-5 position-absolute top-0 start-0 translate-middle">
                <img class="ps-5" src="/icon-design.svg" alt="">
              </div>
            </div>
            <div class="p-4 py-5 bg-white h-100 rounded">
              <h4 class="pb-3">
                Design
              </h4> 

              <span class="text-body">
                Create beautiful, usable interfaces to help shape the future of how the web looks.
              </span>

              <br><br>
              <span class="text-pink fw-bold">
                Get Started
              </span>
            </div>
          </div>

          <div class="col-md-4 mt-2 mb-2 py-4">
            <div class="ps-5 position-relative">
              <div class="ps-5 position-absolute top-0 start-0 translate-middle">
                <img class="ps-5" src="/icon-photography.svg" alt="">
              </div>
            </div>
            <div class="p-4 py-5 bg-white rounded h-100">
              <h4 class="pb-3">
                Photography
              </h4> 
              
              <span class="text-body">
                Explore critical fundamentals like lighting, composition, and focus to capture exceptional photos.
              </span>

              <br><br>
              <span class="text-pink fw-bold">
                Get Started
              </span>
            </div>
          </div>

          <div class="col-md-4 mt-2 mb-2 py-4">
            <div class="ps-5 position-relative">
              <div class="ps-5 position-absolute top-0 start-0 translate-middle">
                <img class="ps-5" src="/icon-crypto.svg" alt="">
              </div>
            </div>
            <div class="p-4 py-5 bg-white rounded">
              <h4 class="pb-3">
                Crypto
              </h4> 

              <span class="text-body">
                All you need to know to get started investing in crypto. Go from beginner to advanced with this 54 hour course.
              </span>

              <br><br>
              <span class="text-pink fw-bold">
                Get Started
              </span>
            </div>
          </div>

          <div class="col-md-4 mt-2 mb-2 py-4">
            <div class="ps-5 position-relative">
              <div class="ps-5 position-absolute top-0 start-0 translate-middle">
                <img class="ps-5" src="/icon-business.svg" alt="">
              </div>
            </div>
            <div class="p-4 py-5 bg-white rounded">
              <h4 class="pb-3">
                Business
              </h4> 

              <span class="text-body">
                A step-by-step playbook to help you start, scale, and sustain your business without outside investment.
              </span>

              <br><br>
              <span class="text-pink fw-bold">
                Get Started
              </span>
            </div>
          </div>

        </div>
      </div>
    </div>

    <div class="bg-dark py-5">
      <div class="container">
        <div class="row">
          <div class="d-flex justify-content-between">
            <div>
              <img src="/logo-light.svg" alt="">
            </div>
            <button class="btn btn-primary border-0 bg-pink-gradient h-100 py-2 px-4">
              Get Started
            </button>
          </div>
        </div>
      </div>
    </div>
    
  </div>
</template>

<style>
body, html {
  font-family: 'Plus Jakarta Sans';
  font-size: 18px;
}

.bg-dark {
  background-color: #13183F;
}

.bg-image {
  background-position: 150% -200px; 
  background-image: url('/image-hero-desktop.png');
  background-repeat: no-repeat;
}

.bg-linear-gradient {
  background: rgb(255,255,255);
  background: linear-gradient(180deg, rgba(255,255,255,1) 0%, rgba(240,241,255,1) 100%);
}

.bg-pink-gradient {
  background: rgb(255,111,72);
  background: linear-gradient(180deg, rgba(255,111,72,1) 0%, rgba(240,42,166,1) 100%);
}

.rounded {
  border-radius: 15px!important;
}

.text-body {
  color: #83869A!important;
}

.btn {
  border-radius: 100px!important;
}

h1 {
  font-size: 56px;
  font-weight: 700;
}

h2 {
  font-size: 40px;
  font-weight: 700;
}

h3 {
  font-size: 32px;
  font-weight: 700;
}

h4 {
  font-size: 24px;
  font-weight: 700;
}

.text-pink {
  color: #F74780;
}
</style>