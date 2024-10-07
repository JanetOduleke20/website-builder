<template>
  <div>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light px-2">
      <a class="navbar-brand" href="#">BlogCreator</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse me-auto" id="navbarNav">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link" href="#features">Features</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#about">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact">Contact</a>
          </li>
        </ul>
      </div>
    </nav>

    <!-- Hero Section -->
    <header class="hero text-white text-center py-5">
      <div class="container">
        <h1 class="display-5">Create Your Blog or E-commerce Website Effortlessly</h1>
        <p class="lead">Build and scale with confidence. From a powerful blog builder to <br> advanced  business solutions—we’ve got you covered.
        </p>
        <a href="#signup" class="btn btn-light btn-lg p-3 rounded-pill">Get Started</a>
      </div>
      <div class="mt-3">
        <img src="../assets/desktop.png " alt="">
      </div>
    </header>

    <!-- Features Section -->
    <section id="features" class="py-5">
      <div class="container">
        <p class="fw-bold text-xl display-5 my-4">One platform, <br>
          many possibilities</p>
        <div class="row">
          <div class="col-md-4">
            <div class="card mb-4">
              <div class="card-body">
                <h5 class="card-title">Build a website</h5>
                <p class="card-text">Design with a full suite of intuitive tools and powerful AI to create the site you want.</p>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card mb-4">
              <div class="card-body">
                <h5 class="card-title">Customizable Templates</h5>
                <p class="card-text">Choose from a variety of beautiful templates to make your blog unique.</p>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card mb-4">
              <div class="card-body">
                <h5 class="card-title">
                  Manage your business</h5>
                <p class="card-text">Streamline your day-to-day with built-in business solutions, tailored to your needs.</p>
              </div>
            </div>
          </div>

        </div>
        <a href="#signup" class="btn btn-dark text-light btn-lg p-3  px-5 rounded-pill">Get Started</a>
      </div>
    </section>

    <!-- Templates section -->
    <section id="templates" class="py-5 ">
      <div class=" text-center bg-dark py-5">
        <p class="fw-bold text-xl display-5 my-4 text-light">Website templates that set you up for success</p>
        <p class="lead text-light">Get a headstart on your journey with 900+ free, customizable website templates, strategically <br> researched and tailored for every industry — or start from a blank canvas on our website builder.
        </p>
        <a href="#signup" class="btn btn-light text-dark my-3 btn-lg p-3  px-5 rounded-pill">Get Started</a>

       
      </div>
    </section>


    <!-- About Section -->
    <section id="about" class="bg-light py-5">
      <div class="container">
        <h2 class="text-center">About Us</h2>
        <p class="text-center">We are a passionate team dedicated to helping writers and business owners create and share their stories or products online. Our platform is designed to be simple yet powerful, enabling anyone to start their journey.</p>
      </div>
    </section>


    <!-- Footer -->
    <footer class="footer text-dark text-center py-3">
      <p>&copy; 2024 BlogCreator. All rights reserved.</p>
      <p><a href="#contact" class="text-white">Contact Us</a></p>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'LandingPage',
};
</script>

<style>
.hero {
  background: url('path_to_your_background_image.jpg') no-repeat center center;
  background-size: cover;
  background-color: rgb(52, 71, 178);
}
</style>
