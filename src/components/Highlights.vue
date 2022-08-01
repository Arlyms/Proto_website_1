<template>
  <div class="highlights">
    <img class="background" src="../assets/mountains.jpg" alt="background mountains">
    <svg xmlns="http://www.w3.org/2000/svg" class="wave" viewBox="0 0 1440 320">
      <path fill="#5d646c" fill-opacity="1" 
      d="M0,192L120,202.7C240,213,480,235,720,240C960,245,1200,235,1320,229.3L1440,
      224L1440,320L1320,320C1200,320,960,320,720,320C480,320,240,320,120,320L0,320Z">
      </path>
    </svg>
  </div>
</template>

<script>
export default {
  name: 'Highlights-container',
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
  .highlights{
    position: relative;
    width: 100vw;
    height: 67vh;
    .background {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }
    .wave{
      position: absolute;
      bottom: 0;
      left: 0;
    }
  } 
</style>
