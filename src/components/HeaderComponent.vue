<template>
  <header class="min-vh-100 position-relative mb-3">
    <nav class="navbar navbar-expand-lg fixed-top navbar-light px-4">
      <div class="container-fluid px-0">
        <router-link class="fs-2 navbar-brand me-5 fw-bold" to="#">
          LO
        </router-link>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav text-uppercase ms-auto">
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link fw-bold" aria-current="page" to="#">about</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link fw-bold" to="#">articles</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link fw-bold" to="#">cart</router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <section id="richard">
      <div class="container-fluid">
        <div class="row min-vh-100">
          <div class="col-lg-6 d-flex flex-column justify-content-end justify-content-xl-between position-relative p-0">
            <div class="wrapper pb-lg-5">
              <div class="position-xl-absolute top-xl-50 start-xl-0 translate-xl-middle-y text-uppercase px-5 text-jumbotron">
                <h2 class="fs-4 text-border-bottom text-border-top">spring</h2>
                <h2 class="fs-4 text-border-bottom py-3">collection</h2>
                <h1 class="display-1 fw-bold pt-3 pb-lg-5">shop</h1>
              </div>
            </div>
            <div class="wrapper bg-title-1 d-flex align-items-center">
              <div class="p-5 h-xxl-75">
                <h2 class="fs-4 text-border-bottom text-uppercase fw-bold mb-4">richard</h2>
                <p class="w-75 ls-1 leading-loose ff-brygada ">A tropical leaf, with delightful shapes perfect for
                  offices and workpaces</p>
                <router-link class="btn-custom-1 ls-1 text-center d-block position-relative" to="#">Add to cart</router-link>
              </div>
            </div>
          </div>
          <div class="col-lg-6 bg-image-1 d-flex flex-column justify-content-end position-relative">
            <div class="d-flex justify-content-end align-items-end align-items-xxl-center pb-4 px-5 text-menu-plant">
              <div
                class="d-flex flex-column justify-content-end text-end p-xl-5 h-xxl-75 ls-1 fw-bold position-relative z-999">
                <router-link class="d-block" to="#richard">richard</router-link>
                <router-link class="d-block" to="#philip">philip</router-link>
                <router-link class="d-block" to="#olivia">olivia</router-link>
                <router-link class="d-block" to="#grace">grace</router-link>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </header>
</template>

<script>
export default {
  name: "HeaderComponent",
}
</script>

