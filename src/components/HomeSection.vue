<template>
  <section class="home overflow-y bg-primary text-light" id="home">
    <div class="container-fluid">
      <div class="row g-2 justify-content-between">
        <div class="col-sm-6 col-md-6 home-text">
          <h1 class="display-2 text-warning">Task Tracker</h1>
          <p class="lead p-2 fs-3">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias
            cupiditate ipsam voluptas iste totam ipsa architecto voluptate
            commodi corrupti, voluptatibus in nobis ullam dolor, sed labore
            tempore! Dolore, natus corrupti?
          </p>
          <a href="#" class="btn btn-outline-warning btn-lg mt-2 px-4 py-3">
            Learn More
          </a>
        </div>
        <div class="col-sm-6 col-md-4 form-area rounded-3 p-4 border shadow">
          <h1 class="my-3 text-dark">Become a citizen</h1>
          <form class="form fs-5">
            <ul class="mb-3 list-group list-group-flush">
              <li class="list-group-item">
                <input
                  class="form-control border-0"
                  type="email"
                  name="email"
                  placeholder="Email"
                  id=""
                />
              </li>
              <li
                class="d-flex p-1 mt-2 text-dark justify-content-between fs-6"
              >
                <div class="form-check">
                  <input
                    class="form-check-input"
                    type="checkbox"
                    value=""
                    id=""
                  />
                  <label class="form-check-label" for="">
                    Subscribe to newletter
                  </label>
                </div>

                <div class="form-check">
                  <input
                    class="form-check-input"
                    type="checkbox"
                    value=""
                    id=""
                  />
                  <label class="form-check-label" for="">
                    Receive promotion email
                  </label>
                </div>
              </li>
              <div class="col-6">
                <input
                  type="button"
                  value="Send"
                  class="btn btn-warning mb-2 mt-4 text-dark form-control p-2"
                />
              </div>
            </ul>
          </form>
          <!-- <div class="mb-1 fs-6"> -->
          <!-- TO OTHER LINKS  -->
          <!-- <a href="#" class="text-light">Forgot password</a>
            &nbsp;
            <span class="text-dark">|</span>
            &nbsp;
            <a href="#" class="text-light">Already a citizen</a> -->
          <!-- </div> -->
        </div>
      </div>
    </div>
    <HomeFooter />
  </section>
  <!-- 
      #0000ff
   -->
</template>

<script>
import HomeFooter from './webimages/HomeFooter.vue'
export default {
  components: {
    HomeFooter,
  },
}
</script>
<style scoped>
section.home {
  position: relative;
  min-height: 80vh;
  padding-top: 4rem;
}
.home h1 {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen,
    Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}
HomeFooter svg {
  position: absolute;
  left: 0;
  bottom: 0;
  vertical-align: bottom;
}
</style>
