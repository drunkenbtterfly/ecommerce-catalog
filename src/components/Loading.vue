<template>
  <div class="custom-loader"></div>
</template>

<script>
export default {
  name: 'LoadingSpinner',
}
</script>


<style scoped>
.custom-loader {
    width: 120px;
    height: 20px;
    background: 
      radial-gradient(circle closest-side,#766DF4 94%,#0000) 50% 50%/calc(50% + 10px) 70% repeat-x 
      #E4E4ED;
    animation: ct9 1s infinite cubic-bezier(0.3,1,0,1);
}

@keyframes ct9 {
  100% {background-position: calc(200% - 5px)}
}</style>