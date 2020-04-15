<template>
  <div>
    <my-appition></my-appition>
    <p>------------------------</p>
    <my-subrtaction></my-subrtaction>
  </div>
</template>

<script>
import Appition from './components/addition';
import Subrtaction from './components/subrtaction';
export default {
  data() {
    return {}
  },
  components: {
    'my-appition': Appition,
    'my-subrtaction': Subrtaction
  }
}
</script>
