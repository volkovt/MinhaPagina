<template>
  <div
    class="d-flex flex-column flex-md-row align-items-center border-bottom shadow"
  >
    <div class="container">
      <ul class="nav col-sm-12 col-md-12 col-lg-12 d-flex justify-content-center">
        <li>
          <router-link to="/" exact class="nav-link text-light fw-bolder">
            <em class="bi bi-house-door-fill"></em>
            ínicio</router-link
          >
        </li>
        <li>
          <router-link to="/stack" class="nav-link text-light fw-bolder">
            <em class="bi bi-stack"></em>
            Stack</router-link
          >
        </li>
        <li>
          <router-link to="/portfolio" class="nav-link text-light fw-bolder">
            <em class="bi bi-book-fill"></em>
            Portfolio</router-link
          >
        </li>
        <li>
          <router-link to="/resume" class="nav-link text-light fw-bolder">
            <em class="bi bi-file-earmark-person-fill"></em>
            Currículo</router-link
          >
        </li>
      </ul>
    </div>
  </div>
</template>

export default {}
