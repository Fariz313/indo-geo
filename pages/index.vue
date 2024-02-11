<template>
  <div>
    <main class="flex-shrink-0">
      <!-- Navigation-->
      <Navbar />
      <!-- Header-->
      <header class="py-5">
        <div class="container px-5 pb-5">
          <div class="row gx-5 align-items-center">
            <div class="col-xxl-5">
              <!-- Header text content-->
              <div class="text-center text-xxl-start">
                <div
                  class="badge bg-gradient-primary-to-secondary text-white mb-4"
                >
                  <div class="text-uppercase">
                    Geolocation &middot; Border &middot; Statistic
                  </div>
                </div>
                <div class="fs-3 fw-light text-muted">
                  Power Your Apps with Precision Geolocation API
                </div>
                <h1 class="display-3 fw-bolder mb-5">
                  <span class="text-gradient d-inline">Indo Geo API</span>
                </h1>
                <div
                  class="d-grid gap-3 d-sm-flex justify-content-sm-center justify-content-xxl-start mb-3"
                >
                  <a
                    class="btn btn-primary btn-lg px-5 py-3 me-sm-3 fs-6 fw-bolder"
                    href="resume.html"
                    >Pricing</a
                  >
                  <a
                    class="btn btn-outline-dark btn-lg px-5 py-3 fs-6 fw-bolder"
                    href="projects.html"
                    >Documentation</a
                  >
                </div>
              </div>
            </div>
            <div class="col-xxl-7">
              <!-- Header profile picture-->
              <HeaderProfilePicture />
            </div>
          </div>
        </div>
      </header>
      <!-- About Section-->
      <section class="bg-light py-5">
        <div class="container px-5">
          <div class="row gx-5 justify-content-center">
            <div class="col-xxl-8">
              <div class="text-center my-5">
                <h2 class="display-5 fw-bolder">
                  <span class="text-gradient d-inline"
                    >IndoGeo API Services</span
                  >
                </h2>
                <p class="text-muted">
                  With our geolocation API, we offer sophisticated and reliable
                  solutions to meet your location needs. Here are some of the
                  things we provide:
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="row px-5 gx-5 text-center">
          <div class="col-3">
            <div class="card border-0 shadow" style="height: 300px">
              <span
                class="w-100 text-center text-gradient"
                style="font-size: 100px"
              >
                <i class="bi bi-geo-fill"></i>
              </span>
              <h4>Accurate Location Data</h4>
              <p class="text-muted p-3">
                We gather data from trusted sources and utilize advanced
                technology to ensure that our geolocation data is accurate and
                up-to-date.
              </p>
            </div>
          </div>
          <div class="col-3">
            <div class="card border-0 shadow" style="height: 300px">
              <span
                class="w-100 text-center text-gradient"
                style="font-size: 100px"
              >
                <i class="bi bi-file-earmark-text-fill"></i>
              </span>
              <h4>Comprehensive Documentation</h4>
              <p class="text-muted p-3">
                With comprehensive and clear documentation, you'll be able to
                integrate our API into your applications or projects quickly and
                easily.
              </p>
            </div>
          </div>
          <div class="col-3">
            <div class="card border-0 shadow" style="height: 300px">
              <span
                class="w-100 text-center text-gradient"
                style="font-size: 100px"
              >
                <i class="bi bi-wrench-adjustable-circle-fill"></i>
              </span>
              <h4>Technical Support</h4>
              <p class="text-muted p-3">
                Our technical support team is ready to assist you with any
                questions or issues you may have at any time, ensuring a smooth
                user experience.
              </p>
            </div>
          </div>
          <div class="col-3">
            <div class="card border-0 shadow" style="height: 300px">
              <span
                class="w-100 text-center text-gradient"
                style="font-size: 100px"
              >
                <i class="bi bi-arrows-angle-expand"></i>
              </span>
              <h4>High Scalability</h4>
              <p class="text-muted p-3">
                With no scalability limitations, our API can handle high-volume
                requests with reliability and high performance.
              </p>
            </div>
          </div>
        </div>
      </section>
      <section class="bg-white py-5">
        <div class="container px-5">
          <div class="row gx-5 justify-content-center">
            <div class="col-xxl-8">
              <div class="text-center my-5">
                <h2 class="display-5 fw-bolder">
                  <span class="text-gradient d-inline">Pricing</span>
                </h2>
                <p class="text-muted">
                  we believe in providing flexible and transparent pricing
                  options to suit your needs. Our pricing plans are designed to
                  offer scalability and affordability, ensuring that you get the
                  most value out of our geolocation API. Choose the plan that
                  best fits your requirements and budget:
                </p>
                <div class="container">
                  <div class="card p-3 border-0 shadow">
                    <span class="text-muted">Start From</span>
                    <h1 class="py-5"><span style="font-weight: 800;font-size:100px">Rp.1000</span> <span class="fs-6">/days</span></h1>
                    <button class="btn btn-primary"> Start Now !</button>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </main>
    <!-- Footer-->
    <footer class="bg-white py-4 mt-auto">
      <div class="container px-5">
        <div
          class="row align-items-center justify-content-between flex-column flex-sm-row"
        >
          <div class="col-auto">
            <div class="small m-0">Copyright &copy; Your Website 2023</div>
          </div>
          <div class="col-auto">
            <a class="small" href="#!">Privacy</a>
            <span class="mx-1">&middot;</span>
            <a class="small" href="#!">Terms</a>
            <span class="mx-1">&middot;</span>
            <a class="small" href="#!">Contact</a>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>
