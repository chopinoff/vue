<template>
  <div class="home">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <ColorPicker/>
    <ScrollEvent/>
    <McSquare/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import ColorPicker from '@/components/ColorPicker.vue'
import ScrollEvent from '@/components/ScrollEvent.vue'
import McSquare from '@/components/McSquare.vue'

export default {
  name: 'HomeView',
  components: {
    // HelloWorld,
    ColorPicker,
    ScrollEvent,
    McSquare,
  }
}
</script>
