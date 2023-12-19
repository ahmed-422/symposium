<template>
    <nav class="navbar">
    <router-link to="#register">Register</router-link>
    <router-link to="/">Home</router-link>
    <router-link to="#about">About</router-link>
    <router-link to="#events">Events</router-link>
    <router-link to="#contact">Contact Us</router-link>
  </nav>
  <div id="app">
    <main>
      <section class="hero">
        <div class="content">
          <h2>Headline</h2>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </div>
      </section>
      <section class="features">
        <h2>Events</h2>
        <div class="feature">
          <i class="icon"></i>
          <h3>Event 1</h3>
          <p>Short description of event 1.</p>
        </div>
        <div class="feature">
          <i class="icon"></i>
          <h3>event 2</h3>
          <p>Short description of event 2.</p>
        </div>
        <div class="feature">
          <i class="icon"></i>
          <h3>event 3</h3>
          <p>Short description of event 3.</p>
        </div>
      </section>
    </main>
    <footer>
      <p>Copyright &copy; 2023 Symposium</p>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'HomeView',
}
</script>