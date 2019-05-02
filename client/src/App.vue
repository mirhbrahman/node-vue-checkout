<template>
  <div id="app">
    <!-- Nav -->
        <div class="hero-head">
          <div class="container">
            <nav class="nav">
              <div class="container">
                <div class="nav-left">
                  <router-link to="/" class="nav-item">Home</router-link>
                </div>
                <span class="nav-toggle">
                  <span></span>
                  <span></span>
                  <span></span>
                </span>
              </div>
            </nav>
          </div>
        </div>

    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {}
  }
}
</script>