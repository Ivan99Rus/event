<template>
  <div class="container authorization-container">
    <h2 class="authorization-title section-title">LOG IN</h2>
    <form action="#" class="authorization-form">
      <div class="input-group authorization__input-group">
        <input type="text" class="authorization-input input" placeholder="Username">
        <input type="password" class="authorization-input input" placeholder="Password">
      </div>
      <div class="authorization-control">
        <div class="authorization-remember">
          <input type="checkbox" id="remember-checkbox" class="authorization-remember__input">
          <label for="remember-checkbox" class="authorization-remember__text">Remember me</label>
        </div>
        <a href="#" class="authorization-forgot">Forgot?</a>
      </div>
      <div class="authorization-btns">
        <button class="authorization-btn btn">LOG IN</button>
        <button class="authorization-btn btn btn_light">Sign up</button>
      </div>
    </form>
  </div>
</template>

<script>



export default {
  name: 'login'
}
</script>

<style lang="scss">
  @import '../assets/styles/auth';
</style>
