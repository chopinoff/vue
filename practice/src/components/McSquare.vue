<template>
  <div>
    <h2 class="m-csquare d-flex">
      <p> m<span>ovie </span> </p>
      <p> c<span>inema </span> </p>
      <p><span class="two"> 2</span><span>square</span> </p>
    </h2>
  </div>
</template>

<script>
export default {

}
</script>

<style>
  .m-csquare {
    position: relative;
    transition: all 1s;
    width: 500px;
    margin: 0 auto;
    font-weight: 700;
  }
  .m-csquare:hover span {
    visibility: visible;
    opacity: 1;
    transition: all 1s;
  }
  .m-csquare:hover .two {
    visibility: hidden;
    opacity: 0;
    transition: all 1s;
  }
  .m-csquare p {
    position: absolute;

  }
  .m-csquare p:nth-child(2) {
    left: 25px;
    transition: all 1s;
  }
  .m-csquare:hover p:nth-child(2) {
    left: 94px;
    transition: all 1s;
  }
  .m-csquare p:nth-child(3) {
    left: 40px;
    transition: all 1s;
  }
  .m-csquare:hover p:nth-child(3) {
    left: 190px;
    transition: all 1s;
  }
  .m-csquare p:hover {

  }
  .m-csquare p span {
    visibility: hidden;
    opacity: 0;
    transition: all 1s;
    font-size: 12px;
  }
  .m-csquare p span:hover {}
  .m-csquare .two {
    visibility: visible;
    opacity: 1;
    transition: all 1s;
    font-size: 20px;
  }
</style>