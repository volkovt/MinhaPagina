<template>
  <div class="main">
    <div class="container-fluid header dflex">
      <ul class="nav col-12 col-lg-auto my-2 my-md-0 text-small justify-content-center">
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
    <div class="container-fluid">
      <router-view><h2>Olá mundo</h2></router-view>
    </div>
    <div class="container-fluid footer">
      <footer className="mt-auto py-3">
        <div className="d-flex justify-content-center">
          <p className="text-light">
            <a href="https://github.com/volkovt" target="_blank" rel="noreferrer">
              <img class="contatos" alt="github" src="@/assets/images/github.png"/>
            </a>
          </p>
          <p className="text-light">
            <a href="https://github.com/volkovt" target="_blank" rel="noreferrer">
              <img class="contatos" alt="linkedin" src="@/assets/images/linkedin.png"/>
            </a>
          </p>
          <p className="text-light">
            <a href="https://github.com/volkovt" target="_blank" rel="noreferrer">
              <img class="contatos" alt="instagram" src="@/assets/images/instagram.png"/>
            </a>
          </p>
        </div>
      </footer>
    </div>
  </div>
</template>

<style lang="scss">
.main {
  height: 100vh;
}

.header {
  background-color: rgb(48, 31, 59);
  padding: .5em 0;
  box-shadow: 3px 3px 5px 6px #ccc;
}

.footer {
  box-shadow: 0px -4px 5px 0px rgba(0, 0, 0, 0.75);
  background-color: rgb(48, 31, 59);
  position: absolute;
  bottom: 0;
}

.contatos {
  margin-left: 10px;
  width: 50px;
  height: 50px;
  border-radius:10%;
  box-shadow: 3px 3px 5px 1px rgba(0, 0, 0, 0.75);
}
/* #nav {
  //background-color: #252525;
  margin-top: 20px;
  padding: 16px 0 16px 0;
  box-shadow: 2px 5px 2px #000913;
  display: flex;
}

#nav a {
  border: 0;
  border-radius: 0.25em;
  flex-wrap: wrap;
  background-color: white;
} */
</style>
