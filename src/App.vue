<template>
  <transition name="fade" mode="out-in">
    <component :is="compname" @change-comp="swapcomp($event)"></component>
  </transition>
</template>

<script>

import Login from './components/Login'
import Signup from './components/Signup'
import Forgot from './components/Forgot'

export default {
  name: 'App',
  components: {
    'login-form': Login,
    'signup-form': Signup,
    'forgot-form': Forgot,
  },
  data: function() {
    return {
      compname: 'login-form'
    }
  },
  methods: {
    swapcomp: function(comp) {
      this.compname = comp;
    }
  }
}
</script>
