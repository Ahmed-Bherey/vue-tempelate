<template>
  <div id="app">
    <div id="nav" class="container">
      <b-navbar toggleable="lg" type="dark" variant="">
        <b-navbar-brand href="#">
          <img src="@/assets/img/logo.png" alt="">
        </b-navbar-brand>
        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
        <b-collapse id="nav-collapse" is-nav>
          <!-- Right aligned nav items -->
          <b-navbar-nav class="ms-auto">
            <b-navbar-nav>
              <b-nav-item href="#">
                <router-link to="/">Home</router-link>
              </b-nav-item>
              <b-nav-item href="#">
                <router-link to="/Services">Services</router-link>
              </b-nav-item>
              <b-nav-item href="#">
                <router-link to="/client">Client</router-link>
              </b-nav-item>
            </b-navbar-nav>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>
    <router-view />
    <footer>
      <div class="container">
      <h5>Copyeight @ Ahmed Bherey</h5>
      <div class="social-icon">
        <font-awesome-icon class="media" :icon="['fab' , 'facebook-f']"/>
        <font-awesome-icon class="media" :icon="['fab' , 'twitter']"/>
        <font-awesome-icon class="media" :icon="['fab' , 'github']"/>
      </div>
      </div>
    </footer>
  </div>
</template>

<style>
#nav img{
  width: 20vh;
}
footer{
  background-color: var(--main-color);
  margin-top: 10px;
  padding: 15px 0;
}
footer .social-icon{
  color: white;
  font-size: 20px;
}
footer .social-icon .media{
  margin: 0 15px;
  cursor: pointer;
}
footer .container{
    display: flex;
  justify-content: space-between;
}
  #nav a.router-link-exact-active {
    color: #42b983;
  }
</style>