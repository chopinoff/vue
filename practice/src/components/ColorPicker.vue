<template>
  <div id="wrap">
    <input type="color">
    <input type="range" id="H" name="H" min="0" max="357"
    @change="changeColor"
    v-model="H"
    >
  </div>
</template>

<script>
export default {
  name : 'ColorPicker',
  data() {
    return {
      H : null,
    }
  },
  methods: {
    changeColor() {
      const H = this.H
      const bg = document.getElementById('wrap')
      let hslColor = `hsl(${H}, 100%, 70%)`
      bg.style.backgroundColor = hslColor
    }
  },
}
</script>
  
<style>
  #wrap {
    height: 200px;
  }
</style>