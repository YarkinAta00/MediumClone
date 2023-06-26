<script>
export default {
  name: 'Navbar',
  components: {
  }
}
</script>

<template>
  <div class="border-bottom border-dark 1px solid fixed-top" style="background-color:rgb(255, 192, 23);">
    <div class="container py-2">
    <nav class="navbar navbar-expand-lg">
      <div class="container-fluid">
        <a class="navbar-brand fs-2" href="#">
          <strong>
            Medium
          </strong>
          </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
          <ul class="navbar-nav px-4">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#"> <small>Our Story</small></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"><small>Membership</small> </a>
            </li>
            <li class="nav-item">
              <a class="nav-link "><small>Write</small> </a>
            </li>
            <li class="nav-item">
              <a class="nav-link "><small>Sign in</small> </a>
            </li>
          </ul>
         <button class="btn btn-dark text-light rounded-5"><small>Get Started</small></button>
        </div>
      </div>
    </nav>
  </div>
  </div>
 
</template>