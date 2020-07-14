<template>
  <div>
    <b-navbar toggleable="lg" type="dark" variant="dark">
      <b-container>
        <b-navbar-brand tag="h1" to="/">
          <svg height="28" width="34" viewBox="0 0 512 512" xmlns="http://www.w3.org/2000/svg">
            <path
              d="M333.075 10.239l160.503 482a14.985 14.985 0 01-2.051 13.521 14.974 14.974 0 01-12.173 6.24h-83.101c-32.505 0-61.143-20.669-71.25-51.416L241.625 210.74a14.829 14.829 0 010-9.492l63.003-190.994z"
              fill="#00a66c"
            />
            <path
              d="M115.751 512H32.65a15.018 15.018 0 01-12.173-6.226 15.031 15.031 0 01-2.065-13.521l159.902-482A15.016 15.016 0 01192.552 0h126.299c4.819 0 9.346 2.314 12.173 6.226a14.991 14.991 0 012.051 13.521L186.986 460.628C176.879 491.346 148.241 512 115.751 512z"
              fill="#4086f4"
            />
            <path
              d="M318.851 0h-62.939v253.56l77.162-233.813a14.992 14.992 0 00-2.051-13.521A15.013 15.013 0 00318.851 0z"
              fill="#4175df"
            />
          </svg>
          EZmovies
        </b-navbar-brand>

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <!-- Right aligned nav items -->
          <b-navbar-nav class="ml-auto">
            <b-nav-item to="/">All Movies</b-nav-item>
            <b-nav-item to="/about">About</b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </b-container>
    </b-navbar>
  </div>
</template>