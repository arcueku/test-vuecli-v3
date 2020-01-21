<template>
  <div>
    <nav class="navbar navbar-expand-md navbar-light bg-light">
      <a class="navbar-brand" href="#">Navbar</a>
      <button
        class="navbar-toggler d-lg-none"
        type="button"
        data-toggle="collapse"
        data-target="#collapsibleNavId"
        aria-controls="collapsibleNavId"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="collapsibleNavId">
        <ul class="navbar-nav mr-auto mt-2 mt-lg-0">
          <li class="nav-item active">
            <a class="nav-link" href="#"
              >Home <span class="sr-only">(current)</span></a
            >
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Link</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">hoge</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">huga</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">powa</a>
          </li>
        </ul>
      </div>
    </nav>

    <div class="row text-center">
      <b-card
        title="Card Title"
        img-src="https://picsum.photos/600/300/?image=25"
        img-alt="Image"
        img-top
        tag="article"
        class="col-md-6 mb-2"
      >
        <b-card-text>
          Some quick example text to build on the card title and make up the
          bulk of the card's content.
        </b-card-text>
        <b-button href="#" block variant="primary">Go somewhere</b-button>
      </b-card>

      <div class="card text-left col-md-6">
        <img
          class="card-img-top"
          src="https://picsum.photos/600/300/?image=27"
          alt=""
        />
        <div class="card-body">
          <h4 class="card-title">Title</h4>
          <p class="card-text">Some quick example text to build on the card title and make up the
          bulk of the card's content.</p>
        </div>
        <a name="" id="" class="btn btn-primary" href="#" role="button"
          >Go somewhere</a
        >
      </div>
    </div>
  </div>
</template>

<style scoped>
.card {
  max-width: 40rem;

}
</style>
