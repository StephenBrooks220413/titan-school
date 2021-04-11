<template>
  <div id="nav">
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg fixed-top navbar-light bg-light">
      <!-- Container wrapper -->
      <div class="container-fluid">
        <!-- Navbar brand -->
        <a class="navbar-brand" href="#">CWD</a>

        <!-- Toggle button -->
        <button
          class="navbar-toggler"
          type="button"
          data-mdb-toggle="collapse"
          data-mdb-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <i class="fas fa-bars"></i>
        </button>

        <!-- Collapsible wrapper -->
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <!-- Left links -->
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <router-link class="nav-link active" to="/">Home</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link active" to="/about">About</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link active" to="/contact">Contact</router-link>
            </li>
            <!-- Navbar dropdown -->
            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle"
                href="#"
                id="navbarDropdown"
                role="button"
                data-mdb-toggle="dropdown"
                aria-expanded="false"
              >
                Menu
              </a>
              <!-- Dropdown menu -->
              <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                <li>
                  <router-link class="dropdown-item active" to="/curriculum"
                    >Curriculum</router-link
                  >
                </li>
                <li>
                  <router-link class="dropdown-item active" to="/enroll"
                    >Enroll Classes</router-link
                  >
                </li>
                <li>
                  <router-link class="dropdown-item active" to="/accounts"
                    >Register/Login</router-link
                  >
                </li>
                <li><hr class="dropdown-divider" /></li>
                <li>
                  <router-link class="dropdown-item active" to="/support"
                    >Support</router-link
                  >
                </li>
              </ul>
            </li>
            <li>
              <router-link class="dropdown-item active" to="/graduation"
                >Certifications</router-link
              >
            </li>
          </ul>
          <!-- Left links -->

          <!-- Search form -->
          <form class="d-flex input-group w-auto">
            <a href="mailto:stephenbrooks714@gmail.com">
              SUPPORT / HELP
            </a>
          </form>
        </div>
        <!-- Collapsible wrapper -->
      </div>
      <!-- Container wrapper -->
    </nav>
  </div>
  <router-view />
</template>

<style lang="scss">
@import "~mdb-ui-kit/css/mdb.min.css";

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  margin-bottom: 60px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: rgb(245, 7, 7);
    }
  }
}
</style>
