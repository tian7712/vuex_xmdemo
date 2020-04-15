<template>
  <div>
    <h1>当前最新的count值为:{{count}}</h1>
    <button>-1</button>
  </div>
</template>
<script>
import { mapState } from 'vuex'
export default {
  data() {
    return {}
  },
  computed: {
      ...mapState(['count'])
  }
}
</script>