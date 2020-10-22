<template>
  <div class="container authorization-container">
    <h2 class="authorization-title section-title">FORGOT?</h2>
    <p class="authorization-subtitle paragraph">
      to reset your password, enter your email or username
    </p>
    <form action="#" class="authorization-form">
      <div class="input-group authorization__input-group">
        <input type="text" class="authorization-input input" placeholder="Username or email">
      </div>
      <div class="authorization-btns">
        <button class="authorization-btn btn_bold btn">RESET YOUR PASS</button>
      </div>
    </form>
  </div>
</template>

<script>
export default {
  template: '#forgot',
  name: 'forgot',
  methods: {

  }
}

</script>

<style lang="scss">
  @import '../assets/styles/auth';
</style>
