<template>
  <div>
    <div class="mb-4">
      <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <a class="navbar-brand" href="#">Navbar</a>
        <button
          class="navbar-toggler"
          type="button"
          data-toggle="collapse"
          data-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item active">
              <!-- <a class="nav-link" href="/"
                >Home <span class="sr-only">(current)</span></a
              > -->
              <nuxt-link to="/" class="nav-link">Home</nuxt-link>
            </li>
          </ul>
        </div>
      </nav>
    </div>
    <slot />
  </div>
</template>
