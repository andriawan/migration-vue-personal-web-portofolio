<template>
  <div>
    <toolbar></toolbar>
  </div>
</template>

<script>

import Toolbar from './Toolbar.vue'

export default {
  components: {Toolbar},
  name: 'Home',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>