<template>
  <section class="pricing" id="pricing">
    <div class="pricing-header px-3 py-3 pt-md-5 pb-md-4 mx-auto text-center">
      <h1 class="display-1 fw-4">Pricing</h1>
      <p class="lead">
        Quickly build an effective pricing table for your potential customers
        with this Bootstrap example. It's built with default Bootstrap
        components and utilities with little customization.
      </p>
    </div>

    <div class="container-fluid">
      <div class="">
        <div class="card-deck row mb-3 text-center">
          <div class="card col-md-4 mb-4 box-shadow">
            <div class="card-header py-2 text-dark">
              <h4 class="my-0 font-weight-normal">Free</h4>
            </div>
            <div class="card-body py-3 mb-2">
              <h1 class="card-title pricing-card-title">
                $0
                <small class="text-muted">/ mo</small>
              </h1>
              <ul class="list-unstyled mt-3 mb-4">
                <li>10 users included</li>
                <li>2 GB of storage</li>
                <li>Email support</li>
                <li>Help center access</li>
              </ul>
              <button
                type="button"
                class="btn btn-lg btn-block btn-outline-primary"
              >
                Sign up for free
              </button>
            </div>
          </div>
          <div class="card col-md-4 mb-4 box-shadow">
            <div class="card-header py-2 text-dark">
              <h4 class="my-0 font-weight-normal">Pro</h4>
            </div>
            <div class="card-body py-3 mb-2">
              <h1 class="card-title pricing-card-title">
                $15
                <small class="text-muted">/ mo</small>
              </h1>
              <ul class="list-unstyled mt-3 mb-4">
                <li>20 users included</li>
                <li>10 GB of storage</li>
                <li>Priority email support</li>
                <li>Help center access</li>
              </ul>
              <button type="button" class="btn btn-lg btn-block btn-primary">
                Get started
              </button>
            </div>
          </div>
          <div class="card col-md-4 mb-4 box-shadow">
            <div class="card-header py-2 text-dark">
              <h4 class="my-0 font-weight-normal">Enterprise</h4>
            </div>
            <div class="card-body py-3 mb-2">
              <h1 class="card-title pricing-card-title">
                $29
                <small class="text-muted">/ mo</small>
              </h1>
              <ul class="list-unstyled mt-3 mb-4">
                <li>30 users included</li>
                <li>15 GB of storage</li>
                <li>Phone and email support</li>
                <li>Help center access</li>
              </ul>
              <button type="button" class="btn btn-lg btn-block btn-primary">
                Contact us
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<style scoped>
section.pricing {
  background: linear-gradient(to left, #ffc107, rgb(255, 247, 22));
  color: rgb(59, 56, 56);
  min-height: 100vh;
  padding-top: 8rem;
  padding-bottom: 3rem;
}
.pricing-header h1 {
  font-family: 'Bebas Neue', cursive;
}
.card {
  color: #e5e5e5;
}

.card-footer,
.card-body {
  background: rgb(46, 45, 45);
}
.card,
.card-footer {
  border-bottom-left-radius: 1rem;
  border-bottom-right-radius: 1rem;
}
.card,
.card-img-top {
  border-top-left-radius: 1rem;
  border-top-right-radius: 1rem;
}
html {
  font-size: 14px;
}
@media (min-width: 768px) {
  html {
    font-size: 16px;
  }
}

.container {
  max-width: 960px;
}

.pricing-header {
  max-width: 700px;
}

.card-deck {
  max-width: 70rem;
  margin: 0 auto;
}
.card-deck .card {
  min-width: 220px;
  min-height: 25rem;
}

.border-top {
  border-top: 1px solid #e5e5e5;
}
.border-bottom {
  border-bottom: 1px solid #e5e5e5;
}

.box-shadow {
  box-shadow: 0 0.25rem 0.75rem rgba(0, 0, 0, 0.05);
}
</style>
