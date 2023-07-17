<template>
  <div id="app">
    <nav>
      <router-link to="/" class="nav-link">Home</router-link>
      <router-link to="/about" class="nav-link">About</router-link>
      <router-link to="/contact" class="nav-link">Contact</router-link>
    </nav>
    <transition name="fade" mode="out-in">
      <router-view></router-view>
    </transition>
  </div>
</template>

<script>
export default {
  name: 'App',
}
</script>

<style>
#app {
  max-width: 600px;
  margin: 0 auto;
  padding: 20px;
}

nav {
  margin-bottom: 20px;
}

.nav-link {
  margin-right: 10px;
  text-decoration: none;
  color: #fff;
  background-color: #333;
  padding: 8px 16px;
  border-radius: 4px;
  font-weight: bold;
  transition: background-color 0.3s;
}

.nav-link:hover {
  background-color: #555;
}

.fade-enter-active,
.fade-leave-active {
  transition: opacity 0.5s;
}

.fade-enter,
.fade-leave-to {
  opacity: 0;
}
</style>