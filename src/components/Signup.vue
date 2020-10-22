<template>
  <div class="container authorization-container">
    <h2 class="authorization-title section-title">SIGN UP</h2>
    <form action="#" class="authorization-form">
      <div class="input-group authorization__input-group">
        <input type="text" class="authorization-input input" placeholder="Username">
        <input type="email" class="authorization-input input" placeholder="Emal">
        <input type="password" class="authorization-input input" placeholder="Password">
        <input type="password" class="authorization-input input" placeholder="Confirm password">
      </div>
      <div class="authorization-btns">
        <button class="authorization-btn btn_bold btn">SIGN UP</button>
        <button 
          class="authorization-btn btn btn_light"
          @click.prevent="on_login()"
        >
          Log in
        </button>
      </div>
    </form>
  </div>
</template>

<script>



export default {
  template: '#signup',
  name: 'signup',
  methods: {
    on_login() {
      this.$emit('change-comp', 'login-form');
    }, 
  }
}
</script>

<style lang="scss">
  @import '../assets/styles/auth';
</style>
